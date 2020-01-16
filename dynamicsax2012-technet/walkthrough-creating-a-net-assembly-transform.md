---
title: 'Walkthrough: Creating a .NET Assembly Transform'
TOCTitle: 'Walkthrough: Creating a .NET Assembly Transform'
ms:assetid: adcd0e8d-e697-4786-9ebc-7cb7981edadd
ms:mtpsurl: https://technet.microsoft.com/library/Gg863930(v=AX.60)
ms:contentKeyID: 35249728
author: Khairunj
ms.date: 04/17/2013
mtps_version: v=AX.60
dev_langs:
- csharp
- xml
---

# Walkthrough: Creating a .NET Assembly Transform 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This walkthrough shows you how to create a .NET transform assembly that can be called from the Application Integration Framework (AIF) pipeline in Microsoft Dynamics AX. In this scenario, the component takes the contents of a comma-separated values (CSV) file that contains customer leads and converts it into XML. What this component does in your installation will vary based on what kind of transformation or processing you need to implement. For information about the AIF pipeline, see [About the AIF Pipeline and Transforms](about-the-aif-pipeline-and-transforms.md).

This walkthrough illustrates the following tasks:

  - Create the .NET assembly

  - Create a program to test the assembly


> [!NOTE]
> <P>This scenario illustrates the creation of an assembly that processes an inbound request. For outbound requests, the same transformation components can be implemented but they are called in the reverse order.</P>



## Prerequisites

To complete this walkthrough, you will need:

  - Visual Studio 2010

## Create the .NET Assembly

The .NET assembly contains the class that gets called from the AIF pipeline when processing a request. This class must implement the ITransform interface which is located in the assembly file Microsoft.Dynamics.IntegrationFramework.dll. This interface contains a single method called Transform that takes three parameters: an input stream, an output stream and a configuration string.

  - Input stream – the request message passed in as a stream.

  - Output stream – the request message after it has been transformed passed out of the method as a stream.

  - Configuration string – a string of data that the developer can specify to be used within the Transform method. This parameter enables you to pass data that is related to the transformation but which is not part of the request stream into the class

### To add a reference to the ITransform assembly

1.  Open Visual Studio and create a new project by selecting **File** \> **New** \> **Project**.

2.  In the **Project types** tree, select **Visual C\#** \> **Windows** and click the **Class Library** template.

3.  Type a project name such as AssemblyTransformTest and click **OK**.

4.  In Solution Explorer, right-click **References** and select **Add Reference**.

5.  On the **Add Reference** form, click the **Browse** tab and browse to assembly in the client\\bin directory. For example, C:\\Program Files\\Microsoft Dynamics AX\\60\\Client\\Bin\\ Microsoft.Dynamics.IntegrationFramework.

6.  Click **OK**.

### To create the transform assembly

1.  Open **Class1.cs**, and then add the following code.
    
    ``` csharp
    using System.Text;
    using System.IO;
    using System.Xml;
    using Microsoft.Dynamics.IntegrationFramework.Transform;
    
    namespace AssemblyTransformTest
    {
        public class Class1 : ITransform
        {
            public void Transform(System.IO.Stream input, System.IO.Stream output, string config)
            {
                StreamReader sreader = new StreamReader(input);
                XmlTextWriter xwriter = new XmlTextWriter(output, Encoding.UTF8);
                string[] fieldArray;
                string[] dataArray;
                string rootName = "Customers";
                string rowName = "Customer";
                int i;
                
                // Get the element names from the headings
                string lineIn = sreader.ReadLine();
                fieldArray = lineIn.Split(',');
    
                // Start writing the XML file.
                xwriter.Formatting = Formatting.Indented;
                xwriter.WriteStartDocument();
                xwriter.WriteComment("customers.xml file");
                xwriter.WriteStartElement(rootName);
    
                lineIn = sreader.ReadLine();
                while (lineIn != null)
                {
                    // Loop through each line of data in the file.
                    xwriter.WriteStartElement(rowName); 
                    dataArray = lineIn.Split(',');
                    // Write each element.
                    for (i = 0; i <= dataArray.GetUpperBound(0); i++)
                    {
                        xwriter.WriteElementString(fieldArray[i], dataArray[i]);
                    }
                    // Write the </Customer> end element.
                    xwriter.WriteEndElement();
                    lineIn = sreader.ReadLine();
                }
                sreader.Close();
                // Write the </Customers> end element.
                xwriter.WriteEndElement();
                xwriter.Close();
            }
        }
    }
    ```
    
    This code expects a stream of data from a CSV file that contains customers. The code parses out the XML element names from the headings in the first line of the file.

2.  Select **Build** \> **Build Solution** to compile the assembly. Now the class is ready to be called from the AIF pipeline. Before you add the class to the pipeline, you must test it to ensure that it is processing the data correctly.

## Create the Program to Test the Assembly

This program is used to test the assembly that you just created. The program reads a CSV file into a stream and passes it to the class that you created in the previous procedure. Then the program both writes the XML output to a file and displays it to the console. The customers.txt CSV input file in this example has the following format.

    Num,AccountName,CustGroup,Currency
    1,Fourth Coffee,20,USD
    2,Graphic Design Institute,20,USD
    3,Lucerne Publishing,20,EUR

Use **Notepad** to create Customers.txt in the c:\\TEMP directory.

### To create the test program

1.  In Solution Explorer, add a new project by right-clicking the AssemblyTransformTest project and selecting **Add** \> **New Project**.

2.  In the **Project types** tree, select **Visual C\#** \> **Windows** and then click the **Console Application** template.

3.  Type a project name such as CallAssemblyTransformTest and then click **OK**.

4.  Right-click the new project and select **Set as Startup Project**.

5.  Add a reference to the assembly that contains the ITransform interface by following steps 4-6 in the previous procedure, “Add a reference to the ITransform assembly.”

6.  Add a reference to the AssemblyTransformTest project by right-clicking **References** and selecting **Add Reference**.

7.  Click on the **Projects** tab, select the **AssemblyTransformTest** project and then click **OK**.

8.  Open **Program.cs** and add the following code.
    
    ``` csharp
    using System;
    using System.IO;
    using AssemblyTransformTest;
    
    
    namespace CallAssemblyTransformTest
    {
        class Program
        {
            static void Main(string[] args)
            {
                AssemblyTransformTest.Class1 transformClass = new Class1();
    
                FileStream input, output;
                
                // Create the two streams to pass into the assembly. You will need to change these 
                // to your file locations.
                input = new FileStream("c:\\temp\\customers.txt", FileMode.Open);
                output = new FileStream("c:\\temp\\customers.xml", FileMode.OpenOrCreate);
    
                // Passes in the customers CSV file and gets back an XML file.
                transformClass.Transform(input, output, "");
    
                // Displays the XML to the console.
                StreamReader sreader = new StreamReader(new FileStream("c:\\temp\\customers.xml", FileMode.Open));
                Console.Write(sreader.ReadToEnd());
                Console.ReadLine();
            }
        }
    }
    ```

9.  Set the **Target framework** property to **.NET Framework 4** on the **Application** tab. To view the properties, right-click on the **AssemblyTransformTest** project in the **Solution Explorer** window and then click **Properties**.

10. Click **F5** to run the project. The program will write the following XML to the output file customers.xml and to the console.
    
    ``` xml
    <?xml version="1.0" encoding="utf-8"?>
    <!--customers.xml file-->
    <Customers>
      <Customer>
        <Num>1</Num>
        <AccountName>Fourth Coffee</AccountName>
        <CustGroup>20</CustGroup>
        <Currency>USD</Currency>
      </Customer>
      <Customer>
        <Num>2</Num>
        <AccountName>Graphic Design Institute</AccountName>
        <CustGroup>20</CustGroup>
        <Currency>USD</Currency>
      </Customer>
      <Customer>
        <Num>3</Num>
        <AccountName>Lucerne Publishing</AccountName>
        <CustGroup>20</CustGroup>
        <Currency>EUR</Currency>
      </Customer>
    </Customers>
    ```

## Next Steps

 Now that you have created a pipeline component and tested it, you are ready to import the assembly. After you import the assembly, it can be called during request processing for a particular integration port. For more information, see [How to: Import a .NET Assembly Transform](how-to-import-a-net-assembly-transform.md).

## See also

[About the AIF Pipeline and Transforms](about-the-aif-pipeline-and-transforms.md)

[Messages and transforms in AIF](messages-and-transforms-in-aif.md)

[Configure processing options](configure-processing-options.md)


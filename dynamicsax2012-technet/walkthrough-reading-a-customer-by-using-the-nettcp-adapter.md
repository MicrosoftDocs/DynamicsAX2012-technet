---
title: 'Walkthrough: Reading a Customer by Using the NetTCP Adapter'
TOCTitle: 'Walkthrough: Reading a Customer by Using the NetTCP Adapter'
ms:assetid: 4ef33d80-fbc0-44ca-9d1a-997af8e54bd3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ710374(v=AX.60)
ms:contentKeyID: 49384266
ms.date: 11/07/2012
mtps_version: v=AX.60
dev_langs:
- csharp
---

# Walkthrough: Reading a Customer by Using the NetTCP Adapter 


_**Applies To:** Microsoft Dynamics AX 2012 R2_

The customer document service is one of the standard document services included with Microsoft Dynamics AX. It enables external systems to read, create, update, and delete customers in the Microsoft Dynamics AX database. This walkthrough illustrates reading a customer by using a basic integration port.

Every document service is represented by a class in the AOT. You can view the **CustCustomerService** in the **Classes** node in the AOT. You can use the CustCustomerService.read method in a C\# client to read a customer after you set up a [basic integration port](using-basic-integration-ports.md). The basic port uses the NET TCP protocol for transport and provides the address for the service operations and the Web Services Description Language (WSDL) uniform resource identifier (URI). You specify the WSDL URI when you add the service reference to the client program in Visual Studio. After you add the service reference, you can call the read method from a C\# client program to read a customer.

This walkthrough illustrates the following tasks:

  - Creating and deploying a basic integration port for the customer service.

  - Creating a command-line client application in C\# that reads a customer record from Microsoft Dynamics AX.

  - Adding the call context to specify a particular partition and company.

  - Reading a customer in Microsoft Dynamics AX.

## Prerequisites

Before you begin, you should be familiar with the following concepts:

  - [Services, service operations and service groups](services-service-operations-and-service-groups.md) in Microsoft Dynamics AX.

  - [Integration ports](integration-ports.md) in Microsoft Dynamics AX.

  - [AIF document services](aif-document-services.md) in Microsoft Dynamics AX.

  - [C\# language](http://msdn.microsoft.com/en-us/library/kx37x362) in Visual Studio 2010.

For a better understanding of the services framework used by Microsoft Dynamics AX, see:

  - [Windows Communication Foundation](http://msdn.microsoft.com/en-us/library/dd456779) (WCF) services model.

To complete this walkthrough, you need the following:

  - Microsoft Dynamics AX must be installed with a developer license.

  - A valid customer record must exist in your Microsoft Dynamics AX implementation.

  - Microsoft Visual Studio 2010 must be installed

  - The customer service must be registered. For information about how to register services, see [Customize service contracts](customize-service-contracts.md).

## Creating and Deploying a Basic Inbound Integration Port for the Customer Service

Microsoft Dynamics AX includes the customer service as a standard document service. You can view the service operations for the CustCustomerService in the **Services** node in the AOT. To expose the service operations, you can create a basic or an enhanced integration port. This procedure illustrates creating a service group, adding the customer service, and then exposing the service group by deploying it on a basic integration port.

### To create a service group and deploy the basic inbound port

1.  Open the Application Object Tree (AOT).

2.  Right-click the **Service Groups** node, and then click **New Service Group**.

3.  Right-click the new service group, and then click **Properties**. Set the **Name** property to **ReadCustomerSG**. Right-click the service group again and then click **Save**.

4.  Right-click **Services** node, and then click **Open New Window**.

5.  Find the **CustCustomerService** and drag it from the **Services** node onto **ReadCustomerSG**. Press CTRL+S to save.

6.  Right-click the **ReadCustomerSG** and **click Deploy Service Group**.
    
    This process may take several minutes. After the service group is successfully deployed, a confirmation message appears in the Infolog.
    
    The port is deployed as a WCF service hosted on your AOS instance. The service operations are defined as the methods on the service class CustCustomerService that are visible in the **Classes** node of the AOT. You call these service operations by using the NetTCP adapter. Deploying the port creates a .NET WSDL assembly. You reference this assembly by using the address in the **WSDL URI** text box that is displayed in the **Inbound ports** form.
    

    > [!TIP]
    > <P>To start this service every time that the AOS is restarted, set the <STRONG>AutoDeploy</STRONG> property for the service group to <STRONG>Yes</STRONG>.</P>



7.  To view the basic port you have created, open the **Inbound ports** form. Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Inbound ports**. The **ReadCustomerSG** port appears in the **Port Names** list as a port of the **Basic** type.

8.  Make note of the address that is displayed in the **WSDL URI** text box.

## Creating a Command-line Client Application in C\#

This section describes how to create a simple client application that synchronously exchanges messages by using the basic integration port you have created. The client application code is written in the C\# programming language. The sample application reads a customer from Microsoft Dynamics AX and then displays the customer account number and other customer information.

1.  Open Visual Studio and create a new console application project in Visual C\#. Name the project **NetTcp Client**.

2.  In **Solution Explorer**, right-click the project name and then click **Add Service Reference**.
    
    The **Add Service Reference** dialog box opens.

3.  In the **Address** text box, enter the WSDL URI from the port that you created in the previous section. In the following example, replace the text YOUR\_AOS\_NAME with the name of the computer that is running your AOS instance. Notice that the final section of the WSDL URI is the name of the basic integration port. Spaces have been added for readability.
    
        http:// YOUR_AOS_NAME:8101/DynamicsAx/Services/ ReadCustomerSG

4.  Click **Go**. Wait for Visual Studio to find the service.

5.  Click **OK** to close the dialog box.

6.  Open Program.cs.

7.  Replace the code with the following example.
    
        using System;
        using System.Collections.Generic;
        using System.Linq;
        using System.Text;
        
        namespace NetTcp_Client
        {
            class Program
            {
                static void Main(string[] args)
                {
                    // Create the service client proxy
        
                    ServiceReference1.CustomerServiceClient c1 = new ServiceReference1.CustomerServiceClient();
        
                    // Create the customer object to receive the response message.
        
                    ServiceReference1.AxdCustomer custResp;
        
                    // Create the entity key list for the request. 
        
                    ServiceReference1.EntityKey[] readRespKeys = new ServiceReference1.EntityKey[1];
                    readRespKeys[0] = new ServiceReference1.EntityKey();
                    readRespKeys[0].KeyData = new ServiceReference1.KeyField[1];
                    readRespKeys[0].KeyData[0] = new ServiceReference1.KeyField();
                    readRespKeys[0].KeyData[0].Field = "AccountNum";
        
                    // Prompt the user for a customer account number.
        
                    Console.WriteLine("Type in a customer account number and then press Enter:");
        
                    // Add the result to the entity key value.
        
                    readRespKeys[0].KeyData[0].Value = Console.ReadLine();
        
                    try
                    {
                        // Try to read the customer.
        
                        custResp = c1.read(null, readRespKeys);
        
                        // Display the information for the customer.
                        Console.WriteLine("For Customer: " + custResp.CustTable[0].AccountNum);
                        Console.WriteLine("Customer name is: " + custResp.CustTable[0].DirParty[0].Name);
                        
                    }
                    catch (Exception e)
                    {
                        Console.WriteLine("Exception: " + e.Message);
                            c1.Abort();
                    }
                    c1.Close();
                }
        
                }
            }

## Adding the Call Context to Specify the Partition and Company

In the example earlier in this topic, you passed null for the first parameter to the read service operation. Passing null causes AIF to use default values in the CallContext object. In the following example you will set values to specify a particular partition and company. For more information about the parameters you can set in the CallContext object, see [Using the Call Context](using-the-call-context.md).

### To add the information for the call context

1.  To create the call context object and set the partition and company, add the following lines after the code to create the service client proxy. Replace the string “MyPartition” with a partition that you are authorized to access at your installation. Replace the string “MyCompany” with a string for a valid company in your installation.
    
    ``` 
                // Create the Call Context
    
                ServiceReference1.CallContext cc = new ServiceReference1.CallContext();
    
                // Set the partition to "MyPartition"
    
                cc.PartitionKey = "MyPartition";
    
                // Set the company to "MyCompany"
    
                cc.Company = "MyCompany";
    ```

2.  The following example illustrates calling the read method and passing the call context as the first parameter.
    
    ``` 
                // Call the read method with the call context as the first parameter
    
                    custResp = c1.read(cc, readRespKeys);
    ```
    

    > [!NOTE]
    > <P>To view the partitions available in your Microsoft Dynamics AX environment, click <STRONG>System Administration</STRONG> &gt; <STRONG>Setup</STRONG> &gt; <STRONG>Partitions</STRONG> to open the <STRONG>Partitions</STRONG> form. To view your current partition and company in the status bar of the Microsoft Dynamics AX client, click <STRONG>File</STRONG> &gt; <STRONG>Tools</STRONG> &gt; <STRONG>Options</STRONG> &gt; <STRONG>Status bar</STRONG> and then select <STRONG>Show company accounts</STRONG> and <STRONG>Show partition</STRONG>.</P>



3.  The following example shows the final version of the code that specifies a partition and a company.
    
    ``` csharp
    using System;
    using System.Collections.Generic;
    using System.Linq;
    using System.Text;
    
    namespace NetTcp_Client
    {
        class Program
        {
            static void Main(string[] args)
            {
                // Create the service client proxy
                ServiceReference1.CustomerServiceClient c1 = new ServiceReference1.CustomerServiceClient();
    
                // Create the Call Context
    
                ServiceReference1.CallContext cc = new ServiceReference1.CallContext();
    
                // Set the partition to "MyPartition"
    
                cc.PartitionKey = "MyPartition";
    
                // Set the company to "MyCompany"
    
                cc.Company = "MyCompany";
    
                // Create the customer object to receive the response message.
    
                ServiceReference1.AxdCustomer custResp;
    
                // Create the entity key list for the request.
    
                ServiceReference1.EntityKey[] readRespKeys = new ServiceReference1.EntityKey[1];
                readRespKeys[0] = new ServiceReference1.EntityKey();
                readRespKeys[0].KeyData = new ServiceReference1.KeyField[1];
                readRespKeys[0].KeyData[0] = new ServiceReference1.KeyField();
                readRespKeys[0].KeyData[0].Field = "AccountNum";
    
                // Prompt the user for a customer account number.
    
                Console.WriteLine("Enter a customer account number:");
    
                // Add the result to the entity key value.
                readRespKeys[0].KeyData[0].Value = Console.ReadLine();
    
    
                try
                {
                    // Try to read the customer.
                    custResp = c1.read(cc, readRespKeys);
    
                    // Display the information for the customer.
                    Console.WriteLine("For Customer: " + custResp.CustTable[0].AccountNum);
                    Console.WriteLine("Customer name is: " + custResp.CustTable[0].DirParty[0].Name);
                    
                }
                catch (Exception e)
                {
                    // Display the exception message. 
    
                      Console.WriteLine("Exception: " + e.Message);
                        c1.Abort();
                }
                c1.Close();
            }
    
            }
        }
    ```

## Reading a customer

To read a customer record, run the client application. You can run the application from Visual Studio or you can use the **Command Prompt** window.

### To run the client application from a Command Prompt window

1.  In Windows, open a **Command Prompt** window.

2.  At the command prompt, run the NetTcp Client application.

3.  When prompted by the application, enter a valid customer account number.

If the customer is successfully read, the application displays the customer account number and the customer name. Otherwise, the application displays an exception message.

## See also

[Partitions, Companies, and Data Isolation in Microsoft Dynamics AX](https://technet.microsoft.com/en-us/library/jj677285\(v=ax.60\))


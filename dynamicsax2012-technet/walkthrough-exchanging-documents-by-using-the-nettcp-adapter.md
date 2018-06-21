---
title: 'Walkthrough: Exchanging documents by using the NetTcp adapter'
TOCTitle: 'Walkthrough: Exchanging documents by using the NetTcp adapter'
ms:assetid: 17efbc86-f582-4a07-8c7b-a028759956b0
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh352231(v=AX.60)
ms:contentKeyID: 36687856
ms.date: 04/17/2013
mtps_version: v=AX.60
---

# Walkthrough: Exchanging documents by using the NetTcp adapter [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The NetTcp adapter provides for synchronous communication by using the Transmission Control Protocol (TCP) transport. This walkthrough demonstrates using an inbound port with the NetTCP adapter to read a sales order from Microsoft Dynamics AX. In this walkthrough, you will create an inbound integration port and then use C\# code to create a command-line program that reads a particular sales order.


> [!NOTE]
> <P>This walkthrough does not demonstrate how to work with security settings, such as those that restrict an exchange to a particular company or partition. For more information about security settings, see <A href="configure-security-for-integration-ports.md">Configure security for integration ports</A>.</P>



## Prerequisites

  - Microsoft Dynamics AX must contain at least one valid sales order.

  - The sales order service must be registered. For information about how to register services, see [Customize service contracts](customize-service-contracts.md).

  - You must have Microsoft Visual Studio 2010 installed and be familiar with how to create simple Visual C\# project.

## Create and configure the integration port

When you create an integration port that uses the NetTCP adapter, AIF publishes a network Uniform Resource Identifier (URI) and a Web Services Description Language (WSDL) address. Together, these addresses provide access to the service operations exposed by the port.

1.  Open the **Inbound ports** form. Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Inbound ports**.

2.  Click **New**.

3.  Name the new integration port SalesOrderRead.

4.  In the **Adapter** list in the **Address** group, select **NetTcp**.

5.  On the **Service contract customizations** FastTab, click **Service operations**.

6.  In the **Select service operations** form, select **SalesSalesOrderService.read** in the **Remaining service operations** list. Click the left arrow to move the service operation to the **Selected service operations** list. Then, close the form.

7.  You can modify the document data policy to match the fields that you want to return in the response. If you do not specify a data policy, then all sales order schema elements are included in the response message by AIF. If you specify a data policy but do not modify the default data policy, then only the default elements are included in the sales order schema.

8.  Activate the integration port.

9.  Make note of the address that is displayed in the **WSDL URI** text box.

10. Close the **Inbound ports** form.

## Create a NetTcp client application

This section describes how to create a simple client application that synchronously exchanges messages with the integration port. The client application code is written in the C\# programming language. The sample application reads a sales order from Microsoft Dynamics AX and then displays the sales order ID and the customer account number.

1.  Open Visual Studio and create a new console application project in Visual C\#. Name the project "TCP Client".

2.  In **Solution Explorer**, right-click the project name and then click **Add Service Reference**.
    
    The **Add Service Reference** dialog box opens.

3.  In the **Address** text box, enter the WSDL URI from the port that you created in the previous section. For example:
    
        http:// YOUR_AOS_NAME:8101/DynamicsAx/Services/SalesOrderRead

4.  Click **Go**. Wait for Visual Studio to find the service.

5.  Click **OK** to close the dialog box.

6.  Open Program.cs. In the code editor, replace the empty Main function with the following C\# code:
    
        static void Main(string[] args)
        {
            // Create the sales order objects
            // Service client
            ServiceReference1.SalesOrderServiceClient cl = new ServiceReference1.SalesOrderServiceClient();
            // Sales order object to receive response
            TCP_Client.ServiceReference1.AxdSalesOrder resp;
        
            // Create the entity key list for the request
            ServiceReference1.EntityKey[] readRespKeys = new ServiceReference1.EntityKey[1];
            readRespKeys[0] = new ServiceReference1.EntityKey();
            readRespKeys[0].KeyData = new ServiceReference1.KeyField[1];
            readRespKeys[0].KeyData[0] = new ServiceReference1.KeyField();
            readRespKeys[0].KeyData[0].Field = "SalesId";
        
            // Ask the user for a sales order ID
            Console.WriteLine("Enter the sales order ID:");
            // Add the result to the entity key value
            readRespKeys[0].KeyData[0].Value = Console.ReadLine();
        
            try
            {
                // Try to read the sales order
                resp = cl.read(null, readRespKeys);
        
                // Display the information from the first sales table
                Console.WriteLine("For sales order: " + resp.SalesTable[0].SalesId);
                Console.WriteLine("Customer Account is: " + resp.SalesTable[0].CustAccount);
            }
            catch (Exception e)
            {
                Console.WriteLine("Exception: " + e.Message);
                cl.Abort();
            }            
            cl.Close();
        }

7.  Build the project.

## Read a sales order

To read a sales order, run the client application.

1.  In Windows, open a Command Prompt window.

2.  At the command prompt, run the TCP Client application.

3.  When prompted by the application, enter a valid sales order ID.

If the sales order is successfully read, the application displays the sales order ID and the customer account number. Otherwise, the application displays an exception message.

## See also

[Managing integration ports](managing-integration-ports.md)

[Walkthrough: Transforming a document](walkthrough-transforming-a-document.md)


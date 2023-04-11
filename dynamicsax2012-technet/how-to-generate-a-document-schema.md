---
title: 'How to: Generate a Document Schema'
TOCTitle: 'How to: Generate a Document Schema'
ms:assetid: 8eb8ac27-5bc1-475f-a186-adf9c467b55e
ms:mtpsurl: https://technet.microsoft.com/library/Bb496531(v=AX.60)
ms:contentKeyID: 35246490
author: tonyafehr
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Generate a Document Schema 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to generate the schema for a document using X++ and how to view the schema for a document exchange on an integration port. Each document has a document schema that defines the rules for data that is serialized to XML or data that is deserialized from XML. If you have an external system that is receiving data from Microsoft Dynamics AX or if you want to send data into Microsoft Dynamics AX via Application Integration Framework (AIF), you must know the XML schema for the documents in the exchange.

## Generate the Schema for a Document

Follow these steps to generate a schema (.xsd) for a document:

1.  In the AOT, navigate to the **Jobs** node, right-click, and select **New job**.

2.  Enter the following code in the editor window, overwriting any existing code.
    
       ```X++
       static void GenerateXSDSchema_Customer(Args _args)
        {
            CustCustomer        customer;
            XML                 xml;
            XMLDocument         xmlDocument;
            FileName            fileName;
            ;
        
            // Instantiate the class.
            customer = new CustCustomer();
        
            // Get the document class schema.
            xml =customer.getSchema();
            xmlDocument = XMLDocument::newXML(xml);
        
            // Save the schema to a file.
            fileName = "c:\\XSDSchema_Customer.xsd";
        
            new FileIoPermission(fileName, 'rw').assert();
            xmlDocument.save(fileName);
            CodeAccessPermission::revertAssert();
        }
       ```

3.  Save your changes.

4.  Right-click the **GenerateXSDSchema\_Customer** job, and then click **Open**. This creates the schema file XSDSchema\_Customer.xsd on the C: drive.

## Generate the Schema for an Integration Port

When you configure an integration port, you associate document service operations with that port. You can specify which fields are enabled for the document on the **Data policies** form. Therefore, the document schema for each integration port can be a subset of the full document schema depending on which fields are enabled. To view the document schema for an integration port, follow these steps:

### To view the schema for an integration port

1.  Open either the **Inbound ports** form or the **Outbound ports** form. To open these forms, follow one of these steps:
    
      - Click **System Administration** \> **Setup** \> **Services and Application Integration Framework** \>**Inbound ports**.
    
      - Click **System Administration** \> **Setup** \> **Services and Application Integration Framework** \>**Outbound ports**.

2.  On the **Service contract customizations** FastTab for one of the inactive ports, select **Customize documents** and then click **Data policies** to open the **Document data policies** form.

3.  In the **Document name** field, click a document name.

4.  Click **View schema** to view the schema for the document that uses the field level restrictions on the **Document data policies** form. For more information about how to set data policies, see [Customize service contracts](customize-service-contracts.md).

5.  To save the schema, click **Save as**, select a file location, and then click **Save**.

## See also

[Document Schemas](document-schemas.md)

[Document Schema Rules](document-schema-rules.md)

[Customize service contracts](customize-service-contracts.md)


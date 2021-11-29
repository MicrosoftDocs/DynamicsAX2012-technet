---
title: 'How to: Create a Service by Using the AIF Document Service Wizard'
TOCTitle: 'How to: Create a Service by Using the AIF Document Service Wizard'
ms:assetid: 6b4c1fe4-a608-4a39-b415-c6b3b1ea4525
ms:mtpsurl: https://technet.microsoft.com/library/Aa609947(v=AX.60)
ms:contentKeyID: 35244794
author: Khairunj
ms.date: 04/17/2013
mtps_version: v=AX.60
---

# How to: Create a Service by Using the AIF Document Service Wizard 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how you can use the **AIF Document Service Wizard** to create a new Application Integration Framework (AIF) document service. You create a new service when you want to expose X++ business logic as a service in Microsoft Dynamics AX. This wizard is designed to simplify and automate the development of service interfaces, service implementations, and data objects. For more information about document services, see [AIF Document Services](aif-document-services.md).

You use the AIF Document Service Wizard to perform the following actions:

  - Analyze the document class query for any best practices issues and optionally correct them.

  - Generate the following classes for the service:
    
      - Ax \<Table\> classes for tables in the query where Ax \<Table\> classes do not yet exist. The Ax\<Table\> classes inherit from the AxInternalBase class and contain accessor methods for each field in each table in the query. For more information, see [About Ax\<Table\> Classes](about-ax-table-classes.md).
    
      - A document service class that contains code that is the default implementation of the selected create, read, update, delete, find, findKeys, getKeys, or getChangedKeys document service operations. The default implementation may be sufficient and may not have to be changed. This class inherits from the [AifDocumentService Class](https://technet.microsoft.com/library/gg768070\(v=ax.60\)).
    
      - The \<Document\> class has generated code and should not be customized. This class inherits from the [AifDocument Class](https://technet.microsoft.com/library/gg767438\(v=ax.60\)).
    
      - The Axd \<document\> class has generated code that is the default implementation of the selected create, read, update, delete, find, findKeys, getKeys, or getChangedKeys document service operations. The default implementation is sufficient for simple implementations and does not have to be customized. For other scenarios, this class must be customized to expose document specific business logic. This class inherits from the [AxdBase Class](https://technet.microsoft.com/library/gg830851\(v=ax.60\)). This class contains the prepareForSave method that is called before a record is saved. It contains a reference to the whole table record. You can add logic here if, for example, one field depends on the value of another.

  - Update any existing Ax \<Table\> classes for tables that are used in the query.

  - Generate a Microsoft Dynamics AX project that contains the following:
    
      - Ax \<Table\> classes for tables in the query where Ax \<Table\> classes do not yet exist. The Ax\<Table\> classes inherit from the AxInternalBase class.
    
      - The document query.
    
      - The generated classes.
    
      - A design view of the service.
    
      - The following two macros:
        
          - Axd\<document\> DCT - contains constants for data object types. This macro is used by the data object classes.
        
          - DataContainerTypes - includes all Axd\<document\> DCT macros in the system.
    
    <!-- end list -->
    
      - A test job for generating the document XML schema definition (XSD).

For more information about the classes that are generated for a service, see [Document Services Classes](document-services-classes.md). Before you use the wizard to create a service, you must create a document query. For more information, see [How to: Create a Document Query](how-to-create-a-document-query.md).


> [!NOTE]
> <P>When you run the wizard, you select the service operations that you want to create. You can select certain service operations at first, and then decide later to create other service operations. Re-running the wizard will generate the code for additional service operations. However, you must add the service operations manually in the <STRONG>Services</STRONG> node of the AOT. Adding the service operations in the <STRONG>Services</STRONG> node exposes them and makes them available on the <STRONG>Inbound ports</STRONG> and <STRONG>Outbound ports</STRONG> forms. For more information, see <A href="customize-service-contracts.md">Customize service contracts</A>.</P>



## Running the AIF Document Service Wizard

After the query has been created, run the AIF Document Service Wizard to create the service.

### To run the AIF Document Service Wizard

1.  Click **Tools** \> **Wizards** \> **AIF Document Service Wizard**, or click **Tools** \> **Application Integration Framework** \> **Create Document Service**. The **Welcome** screen appears.

2.  Click **Next**.

3.  In the **Select document parameters** screen, in the **Query** field, select the Axd \<Document\> query. The **Document name** will default.

4.  Type a descriptive name in the **Document labelabel** field.

5.  Click **Next**.

6.  In the **Select code generation parameters** screen, the **Class names** default based on the query you selected.

7.  Select the service operations that the service will expose. For more information, see [Document Class Service Operations](document-class-service-operations.md).

8.  Click **Next**.

9.  In the **Generate code** screen you can review the artifacts that will be generated. Click **Generate**.

10. The **Completed** screen shows the artifacts that the wizard created.

The service, Axd \<Document\> class, and the Ax\<Table\> classes have been created and are located in the AOT under the **Classes** node. The AIF Document Service Wizard adds a method to the document class for all the service operations (or actions) that are not exposed by the class, and the method will return an error. If you open one of the methods that you did not expose by the class, the generated code should resemble the following example.

```X++
public AifDocumentXml findList(AifQueryCriteria _queryCriteria,
                                   AifSchemaInfo _xsdInfo,
                                   AifConstraintListCollection
                                       _constraintListCollection,
                                   AifPropertyBag _aifPropertyBag)
    {
        throw error(strfmt("@SYS94920"));
    }
```

The wizard also adds "TODO" statements in the generated code; these are code blocks that may require some action by the developer.

## Generate the Document Schema

The document schema or XSD defines the structure and format of the XML that is serialized or deserialized by the document class. In AIF, the schema for each document is generated by iterating through the query associated with the document class. The document schema defines the XML rules for the document. For more information about the document schema, see [Document Schema Rules](document-schema-rules.md).

When you use the AIF Document Service Wizard to create a service, it automatically creates an X++ job that you can run to generate the document schema. Use the following steps to generate the document schema for the service.

### To generate the document schema for the service

1.  Press Ctrl+Shift+P to open the **Projects** form.

2.  Expand the **Private** node and then double-click the Axd \<Document\> project. This project contains all the objects created by the AIF Document Service Wizard that are related to the new service.

3.  Double-click the GenerateXSDSchema\_Axd \<Document\> job to open it in the X++ code editor.

4.  Press F5 to run the job.

When you run this job, it creates a file that contains the schema for all the fields in the document. The file location is c:\\XSDSchema\_Axd\<document\>.xml. Now that the service has been generated, you can [add any custom business logic code](guidelines-for-adding-code-to-document-service-classes.md) to the class or [deploy the service by using an outbound integration port](managing-integration-ports.md).

## See also

[Walkthrough: Creating a Service by Using the AIF Document Service Wizard](walkthrough-creating-a-service-by-using-the-aif-document-service-wizard.md)

[How to: Create a Document Query](how-to-create-a-document-query.md)

[Guidelines for Adding Code to Document Service Classes](guidelines-for-adding-code-to-document-service-classes.md)

[How to: Add a Service Operation to a Service](how-to-add-a-service-operation-to-a-service.md)


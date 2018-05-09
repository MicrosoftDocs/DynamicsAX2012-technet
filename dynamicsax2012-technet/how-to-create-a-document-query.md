---
title: 'How to: Create a Document Query'
TOCTitle: 'How to: Create a Document Query'
ms:assetid: a6dea210-2723-4b34-96b8-8dcaa3ac5f76
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa851589(v=AX.60)
ms:contentKeyID: 35248439
ms.date: 04/17/2013
mtps_version: v=AX.60
---

# How to: Create a Document Query 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to create a document query that is the basis of an Application Integration Framework (AIF) document service. For more information about document services, see [AIF Document Services](aif-document-services.md). The document query is a standard Microsoft Dynamics AX query that is associated with an Axd \<Document\> class. The document query has the following characteristics:

  - In an outbound exchange, the query retrieves the data that populates the document.

  - The document query is the basis from which the document schema is defined. The document schema specifies all the data elements that are valid for the document in either an inbound or outbound exchange.

Document queries are located in the AOT under the **Queries** node. The query name matches that of the document class that has which it is associated. For example, if you create a document query named AxdCustomer then the document class that is generated will be AxdCustomer.


> [!NOTE]
> <P>Before creating a document query and service, you should verify that the Axd class does not already exist. You can view the Axd classes in the AOT. If a class already exists, you must be careful when you name objects so that they do not conflict with the existing AIF classes.</P>



## Finding the Tables

The first step in creating the query is to determine which tables contain the information that is being exchanged by the document.


> [!TIP]
> <P>To find the tables that are used in a functional process, it is helpful to examine the form data sources in the AOT. In order to look up the form in the AOT, you must know the form class name. To find the AOT form class name, open a form that is used in a process. Right-click the form and then select <STRONG>Personalize</STRONG>. You can also use SQL trace to discover what database objects are being accessed during a process. For more information about tracing options, see <A href="https://technet.microsoft.com/en-us/library/aa637570(v=ax.60)">Setting Up the Tracing Tools</A>.</P>



## Creating the Document Query

In this section you will create the document query.

### To create the document query

1.  In the AOT, right-click **Queries**, and then click **New Query**.

2.  Expand the node for the new query that is named something like **Query1**.

3.  In the AOT, right-click **Data Dictionary**, and then click **Open New Window**.

4.  Expand the **Tables** node. Drag the table that contains the information that you want to exchange from the second window onto the **Data Sources** node under the new query in the first window. By default, all the fields in the data source are included in the query.
    
    For more information about how to create a query, see [How to: Create Queries by using the AOT](https://technet.microsoft.com/en-us/library/bb314753\(v=ax.60\)).

5.  Rename the query data source table to remove the \_1.

6.  If your scenario has multiple data sources, see [How to: Add Multiple Data Sources to a Query](https://technet.microsoft.com/en-us/library/aa880078\(v=ax.60\)).

7.  Right-click the new query, click **Properties**, and then set the **Name** property to Axd \<document\>.
    

    > [!NOTE]
    > <P>As a best practice, the query name should always be the same as the document class name. This is especially true when you use the AIF Document Service Wizard to generate the service because it defaults the document class name to that of the query.</P>



8.  Save the query.

After you have created the document query, you can create the service. For more information, see [How to: Create a Service by Using the AIF Document Service Wizard](how-to-create-a-service-by-using-the-aif-document-service-wizard.md).

## See also

[Walkthrough: Creating a Service by Using the AIF Document Service Wizard](walkthrough-creating-a-service-by-using-the-aif-document-service-wizard.md)

[Guidelines for Adding Code to Document Service Classes](guidelines-for-adding-code-to-document-service-classes.md)


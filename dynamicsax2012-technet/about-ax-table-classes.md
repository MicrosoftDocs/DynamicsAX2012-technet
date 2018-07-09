---
title: About Ax<Table> Classes
TOCTitle: About Ax<Table> Classes
ms:assetid: d653f81d-91e5-4542-a0ac-aba7b3d59e0f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa873749(v=AX.60)
ms:contentKeyID: 35252049
ms.date: 04/17/2013
mtps_version: v=AX.60
---

# About Ax\<Table\> Classes [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes the Ax \<Table\> classes in Application Integration Framework (AIF). The Ax \<Table\> classes (sometimes referred to as AxBC classes) manage data, manage access to and from the tables, encapsulate the business logic that is available through the corresponding form, create default field values, and provide an object interface to the individual tables. Along with the Axd \<Document\> classes, the Ax \<Table\> classes provide the business logic implementation for the AIF document services.

The term Ax \<Table\> class is a general reference to specific classes that implement actual table logic. For example, AxSalesTable is an instance of an Ax \<Table\> class. The Ax \<Table\> class inherits from the AxInternalBase class and represents a single table in the AOT.


> [!NOTE]
> <P>If you are using AIF to exchange data, you do not have to know how the Axd&nbsp;&lt;Table&gt; classes interact with other AIF objects. However, if you are creating custom services, this information may be helpful when coding your own classes.</P>



The Ax \<Table\> classes are optional. If you use the **AIF Document Wizard** to create a new document service, the Ax \<Table\> classes are only generated if the option **Generate AxBC Classes** is enabled. For more information, see [Creating New Document Services](creating-new-document-services.md).

You can perform value mappings on document fields at the framework level or by using the Ax \<Table\> classes. If Ax \<Table\> classes are not created, you perform value mapping at the document level using the **Value mapping** form. For more information, see the section “Configure value mapping” in [Configure processing options](configure-processing-options.md).

If you want to perform custom value mapping that is not enabled by the framework then you must use the Ax \<Table\> classes. When the Axd \<Document\> classes use the Ax \<Table\> classes to read or write to the underlying tables, they use the AxdBaseRead and AxdBaseCreate classes. These classes are responsible for reading data from tables or writing records to tables respectively.

If the Ax \<Table\> classes are not generated, the system uses methods from the [AxCommon](https://technet.microsoft.com/en-us/library/gg765455\(v=ax.60\)) class to read and write to the tables. You can see the code used in the prepareForSave and prepareForSaveExtended methods in the Axd \<Document\> class.


> [!NOTE]
> <P>If you create a new table in a query for an existing document, the Ax&nbsp;&lt;Table&gt; classes are not automatically created. In this case, the Axd&nbsp;&lt;Document&gt; classes do not use the Ax&nbsp;&lt;Table&gt; classes. To create Ax&nbsp;&lt;Table&gt; classes, select the options <STRONG>Regenerate data object classes</STRONG> and <STRONG>Update AxBC classes</STRONG> on the <STRONG>Update document service</STRONG> form. You access the <STRONG>Update document service</STRONG> form by opening a development workspace and clicking <STRONG>Tools</STRONG> &gt; <STRONG>Application Integration Framework</STRONG> &gt; <STRONG>Update document service</STRONG>.</P>



## Ax\<Table\> Class Characteristics

Each Ax \<Table\> class has a one-to-one relationship with a database table. This relationship is reflected in the naming convention for Ax \<Table\> classes. Names are constructed by prefixing the table name with Ax. For example, the Ax \<Table\> class for the SalesTable table is AxSalesTable.

The primary purpose of an Ax \<Table\> class is to contain any business logic that is associated with the creation and modification of records in the related table. The Ax \<Table\> classes are responsible for the following operations:

  - Defaulting data – generating default values for fields that are not explicitly set by the calling code.

  - Sequencing – setting fields in the correct order to prevent explicitly set values from being overwritten by the default procedures.

  - Validation – maintaining referential integrity in the database and making sure that any field-level business rules or record-level business rules are adhered to, such as number sequences and application business logic.

  - Value mapping – translating the value of specific fields according to predefined business rules. Value mapping enables external systems to interpret the value of specific fields.

  - Error processing – consolidating error messages when they apply operations across fields so that the calling code has a list of all errors that occur during an exchange.

The Ax \<Table\> classes eliminate the need for the calling application to set database fields in a specific order and to replicate any table-specific business logic.

## Additional Characteristics of Ax\<Table\> Classes

The following are additional characteristics of Ax \<Table\> classes:

  - Typically named with the name of the table that they access prefixed with Ax, such as AxPurchTable or AxPurchLine. The table classes reside in the AOT **Classes** node.

  - Manipulate table records directly.

  - Read from and write to the underlying tables, except where the business logic in Microsoft Dynamics AX will be violated by external updates, such as the TaxTrans table.

  - Are self-contained, and their operations are independent of the calling context.

  - Are independent of the structure of the document in Microsoft Dynamics AX and can be called individually.

  - Implement the AxInternalBase class.
    

    > [!NOTE]
    > <P>The code calling an Ax&nbsp;&lt;Table&gt; class authorizes data access. The Ax&nbsp;&lt;Table&gt; class does not validate whether the user who is calling the class can retrieve data from the database or create or update data in the database.</P>
    > <P>For example, the Axd&nbsp;&lt;Document&gt; class that calls the Ax&nbsp;&lt;Table&gt; classes is invoked by a service acting on behalf of the requesting user. This service must perform the necessary authorization.</P>



## Default Field Values

If default field values are not set by the initValue method, the Ax \<Table\> classes can set default field values that are not set by the calling code. If you must bypass default fields when you insert a record with the Ax \<Table\> class, the code that is calling an Ax \<Table\> class must explicitly set the defaulting procedures to false. Table fields can be defaulted in the Ax \<Table\> class by overriding the setTableFields method. The following code example is from the [AxSalesTable.setTableFields Method](https://technet.microsoft.com/en-us/library/gg937256\(v=ax.60\)).

```X++
    protected void setTableFields()
    {
        SalesTableLinks     salesTableLinks;
        ;
        super();
    
        useMapPolicy = false;
    
        this.setCashDisc();
        this.setCommissionGroup();
        this.setContactPersonId();
        this.setCurrencyCode();
        this.setCustAccount();
        this.setCustGroup();
        this.setDeliveryAddress();
        this.setDeliveryCity();
        this.setDeliveryCountryRegionId();
        this.setDeliveryCounty();
        this.setDeliveryName();
        this.setDeliveryState();
        this.setDeliveryStreet();
        this.setDeliveryZipCode();
        this.setDimension();
        this.setDlvMode();
        this.setDlvReason();
        this.setDlvTerm();
        this.setEmail();
        // Code ommitted.
    }
```

The following example shows the accessor method parmCashDisc in AxSalesTable. This method sets the CashDisc field if the default is not set on the SalesTable.

    public CustCashDiscCode parmCashDisc(CustCashDiscCode _cashDisc = '')
    {
        if (!prmisDefault(_cashDisc))
        {
            this.setField(fieldNum(SalesTable, CashDisc), _cashDisc);
        }
    
        return salesTable.CashDisc;
    }

## See also

[Document Services Classes](document-services-classes.md)

[About Axd\<Document\> Classes](about-axd-document-classes.md)


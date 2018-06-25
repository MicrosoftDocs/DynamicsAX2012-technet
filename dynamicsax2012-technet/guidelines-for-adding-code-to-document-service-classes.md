---
title: Guidelines for Adding Code to Document Service Classes
TOCTitle: Guidelines for Adding Code to Document Service Classes
ms:assetid: 6acef8bb-5e1e-4642-952a-84c04ef768bb
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa653971(v=AX.60)
ms:contentKeyID: 35244790
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Guidelines for Adding Code to Document Service Classes [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic provides business logic concepts to remember when coding the document classes for Application Integration Framework (AIF) data exchange. You can use the AIF Document Service Wizard to generate the document service class, the Axd \<Document\> class and its associated Ax \<Table\> classes. Then you can add business logic code. For more information, see [Document Services Classes](document-services-classes.md).

## Axd\<Document\>Classes

### Duplicates

The AxdBase class does not prevent duplicate documents from being received and created in the database. Duplicates may be acceptable, depending on the nature of the specific document and its business rules.

If duplicates pose a problem for a particular Axd \<Document\> class, you must include code in that class to prevent creating duplicates. For example, duplicate sales orders are accepted in the sales journal table only, which reduces the effect of an incorrect or duplicate sales order document. You can add validation by overriding the document class prepareForSave method and calling any custom methods to perform data validation.

### References

When you enable the outbound methods Axd\<Document\>.read, Axd\<Document\>.readList, Axd\<Document\>.findList, and Axd\<Document\>.findEntityKeyList for an Axd \<Document\> class and the document class query includes the DocuRef table as a data source, make sure that only external notes are sent from the application and that only documents of the type Note are sent. References of other types might contain viruses, worms, Trojan horses, or other malicious code that can harm the system.

### Transaction Veracity

Any Axd \<Document\> classes that expose methods, such as create and createList, and accept inbound documents must include code to prevent creating malicious transactions or other data in the database. For example, we recommend that you implement business logic code to prevent creating orders for large quantities of costly items by customers who have limited credit.

Many inbound documents are usually created as records in a journal so that no transactions are committed to the database until a user has manually posted the journal. In these scenarios, the application data is not as vulnerable. For this reason, you should consider designing custom Axd \<Document\> classes so that transactions are not posted automatically.

Some inbound documents can be inserted directly into a work table, which can pose an exploitable threat to the system that must be mitigated. For example, an inbound exchange rates document that contains incorrect exchange rates can be accepted directly into the exchange rates table. It is important to make sure that the endpoints are defined correctly, secure, and trusted.

### Outbound Exchange Business Logic

In an outbound exchange, the initQueryFromEntityKey method in the document class is called. This method can be used to implement any business logic for the document that is being retrieved from the database before it is sent. For example, the following code in the AxdPurchaseRequisition document class checks to make sure that the purchase order being requested has a status of **Open order**. If the purchase requisition does not have that status, an error is returned and the document is not sent.

    public void initQueryFromEntityKey(AifEntityKey 
        _aifEntityKey = null, boolean _validateEntityKey = false)
    {
        VendPurchOrderJour vendPurchOrderJour;
        ;
    
        if(_aifEntityKey)
        {
            if (_aifEntityKey.parmTableId() == 
                tablenum(VendPurchOrderJour))
            {
                vendPurchOrderJour = 
    SysDictTable::findFromKeyData(_aifEntityKey.parmTableId(),
                                  _aifEntityKey.parmKeyDataMap().pack());
                if (vendPurchOrderJour)
                {
                    if (PurchTable::find(
                        vendPurchOrderJour.PurchId).PurchStatus !=
                        PurchStatus::Backorder)
                    {
                        throw error(strfmt("@SYS89370",vendPurchOrderJour.PurchId));
                    }
                }
            }
        }
    
        super(_aifEntityKey, _validateEntityKey);
    
        this.disableDataSources();
    }

## Ax \<Table\> Classes

### Data Validation

By default, Ax \<Table\> classes do not validate data. Data validation is enabled by calling the Ax\<Table\>.validateInput method with the parameter set to true.

### References

We strongly recommend that you enable only references of the type Note. References of any other types might contain malicious code that can harm the system. The calling code must validate document types (Note, File, Image, Document, and Worksheet) that are permitted to be saved by the AxDocuRef class.

### Cache Methods

When generating an Ax \<Table\> class, two cache methods compile with errors at first.

  - cacheObject method

  - cacheRecordRecord method

These two methods are templates that can be used to cache a record or an object relative to the defaulting logic in the Ax \<Table\> class for inbound services.

To cache \<MyObject\> in the created Ax \<Table\> class, you can use the cacheObject method as a template. Use search and replace to search for cacheObject and replace it with \<MyObject\>. After you have updated the method, it should compile without errors. See the axSalesTable method in AxSalesLine class for an example of a cached object method. For an example of how a cached object method is used relative to defaulting logic in an Ax \<Table\> class, see the setCustAccount method in the AxSalesLine class.

To cache a record of the type \<MyTable\> in the created Ax \<Table\> class, you can use the cacheRecordRecord method as a template. Use search and replace to search for cacheRecord and replace it with \<MyTable\>. After you have updated the method, it should compile without errors. For an example of a cached record method, see the inventTableRecord method in the AxSalesLine class. For an example of how a cached record method is used relative to defaulting logic in an Ax \<Table\> class, see the setSalesUnit method in the AxSalesLine class.

## See also

[Creating New Document Services](creating-new-document-services.md)


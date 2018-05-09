---
title: PublishingProcessor.PublishingPortalSiteCollectionUris Property  (Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector)
TOCTitle: PublishingPortalSiteCollectionUris Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.PublishingProcessor.PublishingPortalSiteCollectionUris
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sp.publishing.connector.publishingprocessor.publishingportalsitecollectionuris(v=AX.60)
ms:contentKeyID: 65316705
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.PublishingProcessor.PublishingPortalSiteCollectionUris
dev_langs:
- CSharp
- C++
- VB
---

# PublishingPortalSiteCollectionUris Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector (in Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.dll)

## Syntax

``` vb
'Declaration
Public Property PublishingPortalSiteCollectionUris As IEnumerable(Of Uri)
    Get
    Private Set
'Usage
Dim instance As PublishingProcessor
Dim value As IEnumerable(Of Uri)

value = instance.PublishingPortalSiteCollectionUris
```

``` csharp
public IEnumerable<Uri> PublishingPortalSiteCollectionUris { get; private set; }
```

``` c++
public:
property IEnumerable<Uri^>^ PublishingPortalSiteCollectionUris {
    IEnumerable<Uri^>^ get ();
    private: void set (IEnumerable<Uri^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[Uri](https://technet.microsoft.com/en-us/library/txt7706a\(v=ax.60\))\>  

## See Also

#### Reference

[PublishingProcessor Class](publishingprocessor-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector.md)

[Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector Namespace](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-namespace.md)


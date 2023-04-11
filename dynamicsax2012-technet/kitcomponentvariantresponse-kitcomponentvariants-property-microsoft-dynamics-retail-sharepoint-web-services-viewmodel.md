---
title: KitComponentVariantResponse.KitComponentVariants Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: KitComponentVariants Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.KitComponentVariantResponse.KitComponentVariants
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.kitcomponentvariantresponse.kitcomponentvariants(v=AX.60)
ms:contentKeyID: 62206841
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.KitComponentVariantResponse.KitComponentVariants
dev_langs:
- CSharp
- C++
- VB
---

# KitComponentVariants Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or set the information for a specific kit configuration.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property KitComponentVariants As IEnumerable(Of StorefrontListItem)
    Get
    Set
'Usage
Dim instance As KitComponentVariantResponse
Dim value As IEnumerable(Of StorefrontListItem)

value = instance.KitComponentVariants

instance.KitComponentVariants = value
```

``` csharp
[DataMemberAttribute]
public IEnumerable<StorefrontListItem> KitComponentVariants { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<StorefrontListItem^>^ KitComponentVariants {
    IEnumerable<StorefrontListItem^>^ get ();
    void set (IEnumerable<StorefrontListItem^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[StorefrontListItem](storefrontlistitem-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[KitComponentVariantResponse Class](kitcomponentvariantresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)


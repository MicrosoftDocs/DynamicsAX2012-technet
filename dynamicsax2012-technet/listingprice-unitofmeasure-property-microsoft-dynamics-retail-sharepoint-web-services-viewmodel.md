---
title: ListingPrice.UnitOfMeasure Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: UnitOfMeasure Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ListingPrice.UnitOfMeasure
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.listingprice.unitofmeasure(v=AX.60)
ms:contentKeyID: 62202304
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ListingPrice.UnitOfMeasure
dev_langs:
- CSharp
- C++
- VB
---

# UnitOfMeasure Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the unit of measure.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property UnitOfMeasure As String
    Get
    Set
'Usage
Dim instance As ListingPrice
Dim value As String

value = instance.UnitOfMeasure

instance.UnitOfMeasure = value
```

``` csharp
[DataMemberAttribute]
public string UnitOfMeasure { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ UnitOfMeasure {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ListingPrice Class](listingprice-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)


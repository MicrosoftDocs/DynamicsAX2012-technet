---
title: ListingPrice.InventoryDimensionId Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: InventoryDimensionId Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ListingPrice.InventoryDimensionId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.listingprice.inventorydimensionid(v=AX.60)
ms:contentKeyID: 62204808
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ListingPrice.InventoryDimensionId
dev_langs:
- CSharp
- C++
- VB
---

# InventoryDimensionId Property

Gets or sets the optional dimension identifier (for variant) that this listing price applies to.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property InventoryDimensionId As String
    Get
    Set
'Usage
Dim instance As ListingPrice
Dim value As String

value = instance.InventoryDimensionId

instance.InventoryDimensionId = value
```

``` csharp
[DataMemberAttribute]
public string InventoryDimensionId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ InventoryDimensionId {
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


---
title: TransactionItem.VariantInventoryDimensionId Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: VariantInventoryDimensionId Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.TransactionItem.VariantInventoryDimensionId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.transactionitem.variantinventorydimensionid(v=AX.60)
ms:contentKeyID: 62204856
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.TransactionItem.VariantInventoryDimensionId
dev_langs:
- CSharp
- C++
- VB
---

# VariantInventoryDimensionId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the VariantDimension ID.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property VariantInventoryDimensionId As String
    Get
    Set
'Usage
Dim instance As TransactionItem
Dim value As String

value = instance.VariantInventoryDimensionId

instance.VariantInventoryDimensionId = value
```

``` csharp
[DataMemberAttribute]
public string VariantInventoryDimensionId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ VariantInventoryDimensionId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TransactionItem Class](transactionitem-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)


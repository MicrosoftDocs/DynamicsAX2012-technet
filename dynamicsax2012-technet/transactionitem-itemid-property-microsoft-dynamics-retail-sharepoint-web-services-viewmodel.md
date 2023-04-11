---
title: TransactionItem.ItemId Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: ItemId Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.TransactionItem.ItemId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.transactionitem.itemid(v=AX.60)
ms:contentKeyID: 62204617
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.TransactionItem.ItemId
dev_langs:
- CSharp
- C++
- VB
---

# ItemId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the Item ID.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ItemId As String
    Get
    Set
'Usage
Dim instance As TransactionItem
Dim value As String

value = instance.ItemId

instance.ItemId = value
```

``` csharp
[DataMemberAttribute]
public string ItemId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ItemId {
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


---
title: TransactionItem.DiscountValue Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: DiscountValue Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.TransactionItem.DiscountValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.transactionitem.discountvalue(v=AX.60)
ms:contentKeyID: 62203007
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.TransactionItem.DiscountValue
dev_langs:
- CSharp
- C++
- VB
---

# DiscountValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the discount value.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DiscountValue As String
    Get
    Set
'Usage
Dim instance As TransactionItem
Dim value As String

value = instance.DiscountValue

instance.DiscountValue = value
```

``` csharp
[DataMemberAttribute]
public string DiscountValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ DiscountValue {
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


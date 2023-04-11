---
title: Transaction.GrandTotal Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: GrandTotal Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.Transaction.GrandTotal
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.transaction.grandtotal(v=AX.60)
ms:contentKeyID: 62206330
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.Transaction.GrandTotal
dev_langs:
- CSharp
- C++
- VB
---

# GrandTotal Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the cart grand total.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property GrandTotal As String
    Get
    Set
'Usage
Dim instance As Transaction
Dim value As String

value = instance.GrandTotal

instance.GrandTotal = value
```

``` csharp
[DataMemberAttribute]
public string GrandTotal { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ GrandTotal {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[Transaction Class](transaction-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)


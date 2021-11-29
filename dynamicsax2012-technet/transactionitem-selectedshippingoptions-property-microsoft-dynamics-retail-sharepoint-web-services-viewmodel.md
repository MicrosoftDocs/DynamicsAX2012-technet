---
title: TransactionItem.SelectedShippingOptions Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: SelectedShippingOptions Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.TransactionItem.SelectedShippingOptions
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.transactionitem.selectedshippingoptions(v=AX.60)
ms:contentKeyID: 62206953
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.TransactionItem.SelectedShippingOptions
dev_langs:
- CSharp
- C++
- VB
---

# SelectedShippingOptions Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the selected shipping options.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SelectedShippingOptions As SelectedItemShippingOptions
    Get
    Private Set
'Usage
Dim instance As TransactionItem
Dim value As SelectedItemShippingOptions

value = instance.SelectedShippingOptions
```

``` csharp
[DataMemberAttribute]
public SelectedItemShippingOptions SelectedShippingOptions { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property SelectedItemShippingOptions^ SelectedShippingOptions {
    SelectedItemShippingOptions^ get ();
    private: void set (SelectedItemShippingOptions^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SelectedItemShippingOptions](selecteditemshippingoptions-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
Returns [SelectedItemShippingOptions](selecteditemshippingoptions-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md).  

## See Also

#### Reference

[TransactionItem Class](transactionitem-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)


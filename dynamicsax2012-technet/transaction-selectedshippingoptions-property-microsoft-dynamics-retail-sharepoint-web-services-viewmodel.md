---
title: Transaction.SelectedShippingOptions Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: SelectedShippingOptions Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.Transaction.SelectedShippingOptions
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.transaction.selectedshippingoptions(v=AX.60)
ms:contentKeyID: 62203359
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.Transaction.SelectedShippingOptions
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
Public Property SelectedShippingOptions As SelectedOrderShippingOptions
    Get
    Private Set
'Usage
Dim instance As Transaction
Dim value As SelectedOrderShippingOptions

value = instance.SelectedShippingOptions
```

``` csharp
[DataMemberAttribute]
public SelectedOrderShippingOptions SelectedShippingOptions { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property SelectedOrderShippingOptions^ SelectedShippingOptions {
    SelectedOrderShippingOptions^ get ();
    private: void set (SelectedOrderShippingOptions^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SelectedOrderShippingOptions](selectedordershippingoptions-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
Returns [SelectedOrderShippingOptions](selectedordershippingoptions-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md).  

## See Also

#### Reference

[Transaction Class](transaction-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)


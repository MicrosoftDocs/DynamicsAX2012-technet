---
title: SelectedShippingOptions.DeliveryMethodText Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: DeliveryMethodText Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SelectedShippingOptions.DeliveryMethodText
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.selectedshippingoptions.deliverymethodtext(v=AX.60)
ms:contentKeyID: 62204317
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SelectedShippingOptions.DeliveryMethodText
dev_langs:
- CSharp
- C++
- VB
---

# DeliveryMethodText Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the selected delivery method.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DeliveryMethodText As String
    Get
    Set
'Usage
Dim instance As SelectedShippingOptions
Dim value As String

value = instance.DeliveryMethodText

instance.DeliveryMethodText = value
```

``` csharp
[DataMemberAttribute]
public string DeliveryMethodText { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ DeliveryMethodText {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[SelectedShippingOptions Class](selectedshippingoptions-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)


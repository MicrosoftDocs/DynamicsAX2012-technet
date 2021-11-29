---
title: ShippingOption.ShippingType Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: ShippingType Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShippingOption.ShippingType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.shippingoption.shippingtype(v=AX.60)
ms:contentKeyID: 62204425
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShippingOption.ShippingType
dev_langs:
- CSharp
- C++
- VB
---

# ShippingType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the shipping option type.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ShippingType As String
    Get
    Set
'Usage
Dim instance As ShippingOption
Dim value As String

value = instance.ShippingType

instance.ShippingType = value
```

``` csharp
[DataMemberAttribute]
public string ShippingType { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ShippingType {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ShippingOption Class](shippingoption-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)


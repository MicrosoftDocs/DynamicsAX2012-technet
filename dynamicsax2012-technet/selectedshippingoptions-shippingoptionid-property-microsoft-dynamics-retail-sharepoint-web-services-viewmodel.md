---
title: SelectedShippingOptions.ShippingOptionId Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: ShippingOptionId Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SelectedShippingOptions.ShippingOptionId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.selectedshippingoptions.shippingoptionid(v=AX.60)
ms:contentKeyID: 62202010
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SelectedShippingOptions.ShippingOptionId
dev_langs:
- CSharp
- C++
- VB
---

# ShippingOptionId Property

Gets or sets the selected shipping option.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ShippingOptionId As String
    Get
    Set
'Usage
Dim instance As SelectedShippingOptions
Dim value As String

value = instance.ShippingOptionId

instance.ShippingOptionId = value
```

``` csharp
[DataMemberAttribute]
public string ShippingOptionId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ShippingOptionId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[SelectedShippingOptions Class](selectedshippingoptions-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)


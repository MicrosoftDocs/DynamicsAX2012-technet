---
title: SelectedShippingOptions.DeliveryMethodId Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: DeliveryMethodId Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SelectedShippingOptions.DeliveryMethodId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.selectedshippingoptions.deliverymethodid(v=AX.60)
ms:contentKeyID: 62204028
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SelectedShippingOptions.DeliveryMethodId
dev_langs:
- CSharp
- C++
- VB
---

# DeliveryMethodId Property

Gets or sets the selected delivery method.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DeliveryMethodId As String
    Get
    Set
'Usage
Dim instance As SelectedShippingOptions
Dim value As String

value = instance.DeliveryMethodId

instance.DeliveryMethodId = value
```

``` csharp
[DataMemberAttribute]
public string DeliveryMethodId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ DeliveryMethodId {
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


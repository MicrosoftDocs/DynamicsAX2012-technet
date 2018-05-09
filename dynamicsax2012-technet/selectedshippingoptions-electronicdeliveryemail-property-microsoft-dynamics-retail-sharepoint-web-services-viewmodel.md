---
title: SelectedShippingOptions.ElectronicDeliveryEmail Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: ElectronicDeliveryEmail Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SelectedShippingOptions.ElectronicDeliveryEmail
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.selectedshippingoptions.electronicdeliveryemail(v=AX.60)
ms:contentKeyID: 62202054
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SelectedShippingOptions.ElectronicDeliveryEmail
dev_langs:
- CSharp
- C++
- VB
---

# ElectronicDeliveryEmail Property

Gets or sets the electronic delivery email address.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ElectronicDeliveryEmail As String
    Get
    Set
'Usage
Dim instance As SelectedShippingOptions
Dim value As String

value = instance.ElectronicDeliveryEmail

instance.ElectronicDeliveryEmail = value
```

``` csharp
[DataMemberAttribute]
public string ElectronicDeliveryEmail { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ElectronicDeliveryEmail {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## Remarks

This is supposed to be set with email delivery.

## See Also

#### Reference

[SelectedShippingOptions Class](selectedshippingoptions-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)


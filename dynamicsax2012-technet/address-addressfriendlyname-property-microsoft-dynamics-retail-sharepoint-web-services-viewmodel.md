---
title: Address.AddressFriendlyName Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: AddressFriendlyName Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.Address.AddressFriendlyName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.address.addressfriendlyname(v=AX.60)
ms:contentKeyID: 62207671
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.Address.AddressFriendlyName
dev_langs:
- CSharp
- C++
- VB
---

# AddressFriendlyName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the adddress friendly name.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property AddressFriendlyName As String
    Get
    Set
'Usage
Dim instance As Address
Dim value As String

value = instance.AddressFriendlyName

instance.AddressFriendlyName = value
```

``` csharp
[DataMemberAttribute]
public string AddressFriendlyName { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ AddressFriendlyName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[Address Class](address-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)


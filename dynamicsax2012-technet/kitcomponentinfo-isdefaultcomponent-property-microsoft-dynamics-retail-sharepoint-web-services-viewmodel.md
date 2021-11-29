---
title: KitComponentInfo.IsDefaultComponent Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: IsDefaultComponent Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.KitComponentInfo.IsDefaultComponent
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.kitcomponentinfo.isdefaultcomponent(v=AX.60)
ms:contentKeyID: 62204469
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.KitComponentInfo.IsDefaultComponent
dev_langs:
- CSharp
- C++
- VB
---

# IsDefaultComponent Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether the current kit line product is used as the default component of the kit.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsDefaultComponent As Boolean
    Get
    Set
'Usage
Dim instance As KitComponentInfo
Dim value As Boolean

value = instance.IsDefaultComponent

instance.IsDefaultComponent = value
```

``` csharp
[DataMemberAttribute]
public bool IsDefaultComponent { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsDefaultComponent {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[KitComponentInfo Class](kitcomponentinfo-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)


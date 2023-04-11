---
title: BooleanResponse.IsTrue Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: IsTrue Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.BooleanResponse.IsTrue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.booleanresponse.istrue(v=AX.60)
ms:contentKeyID: 62206042
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.BooleanResponse.IsTrue
dev_langs:
- CSharp
- C++
- VB
---

# IsTrue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Indicator for boolean response.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsTrue As Boolean
    Get
    Set
'Usage
Dim instance As BooleanResponse
Dim value As Boolean

value = instance.IsTrue

instance.IsTrue = value
```

``` csharp
[DataMemberAttribute]
public bool IsTrue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsTrue {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[BooleanResponse Class](booleanresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)


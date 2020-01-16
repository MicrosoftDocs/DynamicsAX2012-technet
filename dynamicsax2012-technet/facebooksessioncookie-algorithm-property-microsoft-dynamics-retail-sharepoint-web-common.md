---
title: FacebookSessionCookie.Algorithm Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Common)
TOCTitle: Algorithm Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Common.FacebookSessionCookie.Algorithm
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.common.facebooksessioncookie.algorithm(v=AX.60)
ms:contentKeyID: 62206946
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Common.FacebookSessionCookie.Algorithm
dev_langs:
- CSharp
- C++
- VB
---

# Algorithm Property

Algorithm.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Common](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Algorithm As String
    Get
    Set
'Usage
Dim instance As FacebookSessionCookie
Dim value As String

value = instance.Algorithm

instance.Algorithm = value
```

``` csharp
[DataMemberAttribute]
public string Algorithm { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Algorithm {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[FacebookSessionCookie Class](facebooksessioncookie-class-microsoft-dynamics-retail-sharepoint-web-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Common Namespace](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)


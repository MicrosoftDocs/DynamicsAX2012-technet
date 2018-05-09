---
title: FacebookSessionCookie.Issued_At Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Common)
TOCTitle: Issued_At Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Common.FacebookSessionCookie.Issued_At
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.common.facebooksessioncookie.issued_at(v=AX.60)
ms:contentKeyID: 62205049
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Common.FacebookSessionCookie.Issued_At
dev_langs:
- CSharp
- C++
- VB
---

# Issued\_At Property

Issued At.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Common](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Issued_At As String
    Get
    Set
'Usage
Dim instance As FacebookSessionCookie
Dim value As String

value = instance.Issued_At

instance.Issued_At = value
```

``` csharp
[DataMemberAttribute]
public string Issued_At { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Issued_At {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[FacebookSessionCookie Class](facebooksessioncookie-class-microsoft-dynamics-retail-sharepoint-web-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Common Namespace](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)


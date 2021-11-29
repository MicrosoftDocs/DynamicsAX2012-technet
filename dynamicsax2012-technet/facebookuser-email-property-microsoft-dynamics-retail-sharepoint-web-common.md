---
title: FacebookUser.Email Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Common)
TOCTitle: Email Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Common.FacebookUser.Email
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.common.facebookuser.email(v=AX.60)
ms:contentKeyID: 62203606
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Common.FacebookUser.Email
dev_langs:
- CSharp
- C++
- VB
---

# Email Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Primary email.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Common](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Email As String
    Get
    Set
'Usage
Dim instance As FacebookUser
Dim value As String

value = instance.Email

instance.Email = value
```

``` csharp
[DataMemberAttribute]
public string Email { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Email {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[FacebookUser Class](facebookuser-class-microsoft-dynamics-retail-sharepoint-web-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Common Namespace](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)


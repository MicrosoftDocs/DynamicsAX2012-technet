---
title: FacebookSessionCookie.User_Id Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Common)
TOCTitle: User_Id Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Common.FacebookSessionCookie.User_Id
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.common.facebooksessioncookie.user_id(v=AX.60)
ms:contentKeyID: 62207130
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Common.FacebookSessionCookie.User_Id
dev_langs:
- CSharp
- C++
- VB
---

# User\_Id Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

User ID.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Common](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property User_Id As String
    Get
    Set
'Usage
Dim instance As FacebookSessionCookie
Dim value As String

value = instance.User_Id

instance.User_Id = value
```

``` csharp
[DataMemberAttribute]
public string User_Id { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ User_Id {
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


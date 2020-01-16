---
title: FacebookUser.First_Name Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Common)
TOCTitle: First_Name Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Common.FacebookUser.First_Name
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.common.facebookuser.first_name(v=AX.60)
ms:contentKeyID: 62202285
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Common.FacebookUser.First_Name
dev_langs:
- CSharp
- C++
- VB
---

# First\_Name Property

First name.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Common](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property First_Name As String
    Get
    Set
'Usage
Dim instance As FacebookUser
Dim value As String

value = instance.First_Name

instance.First_Name = value
```

``` csharp
[DataMemberAttribute]
public string First_Name { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ First_Name {
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


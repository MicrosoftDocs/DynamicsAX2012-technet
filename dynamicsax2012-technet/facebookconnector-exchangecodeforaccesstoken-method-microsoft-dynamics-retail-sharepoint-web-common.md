---
title: FacebookConnector.ExchangeCodeForAccessToken Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Common)
TOCTitle: ExchangeCodeForAccessToken Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Common.FacebookConnector.ExchangeCodeForAccessToken(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.common.facebookconnector.exchangecodeforaccesstoken(v=AX.60)
ms:contentKeyID: 62203014
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Common.FacebookConnector.ExchangeCodeForAccessToken
dev_langs:
- CSharp
- C++
- VB
---

# ExchangeCodeForAccessToken Method

Exchange the Facebook "code" for an access token.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Common](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Function ExchangeCodeForAccessToken ( _
    code As String _
) As Boolean
'Usage
Dim instance As FacebookConnector
Dim code As String
Dim returnValue As Boolean

returnValue = instance.ExchangeCodeForAccessToken(code)
```

``` csharp
public bool ExchangeCodeForAccessToken(
    string code
)
```

``` c++
public:
bool ExchangeCodeForAccessToken(
    String^ code
)
```

#### Parameters

  - code  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[FacebookConnector Class](facebookconnector-class-microsoft-dynamics-retail-sharepoint-web-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Common Namespace](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)


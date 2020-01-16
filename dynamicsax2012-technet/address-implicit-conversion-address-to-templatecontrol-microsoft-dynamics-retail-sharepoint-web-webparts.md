---
title: Address Implicit Conversion (Address to TemplateControl) (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: Implicit Conversion (Address to TemplateControl)
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Address.op_Implicit(Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Address)~System.Web.UI.TemplateControl
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.webparts.address.op_implicit(v=AX.60)
ms:contentKeyID: 62206833
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Address.Implicit
dev_langs:
- CSharp
- C++
- VB
---

# Implicit Conversion (Address to TemplateControl)

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
Public Shared Widening Operator CType ( _
    target As Address _
) As TemplateControl
'Usage
Dim input As Address
Dim output As TemplateControl

output = CType(input, TemplateControl)
```

``` csharp
public static implicit operator TemplateControl (
    Address target
)
```

``` c++
static implicit operator TemplateControl^ (
    Address^ target
)
```

#### Parameters

  - target  
    Type: [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Address](address-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)  

#### Return Value

Type: [System.Web.UI.TemplateControl](https://technet.microsoft.com/library/2174ac61\(v=ax.60\))  
Returns [TemplateControl](https://technet.microsoft.com/library/2174ac61\(v=ax.60\)).  

## See Also

#### Reference

[Address Class](address-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)


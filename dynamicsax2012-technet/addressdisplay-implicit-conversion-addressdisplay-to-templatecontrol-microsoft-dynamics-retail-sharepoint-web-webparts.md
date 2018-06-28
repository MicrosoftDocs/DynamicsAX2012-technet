---
title: AddressDisplay Implicit Conversion (AddressDisplay to TemplateControl) (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: Implicit Conversion (AddressDisplay to TemplateControl)
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.AddressDisplay.op_Implicit(Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.AddressDisplay)~System.Web.UI.TemplateControl
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.webparts.addressdisplay.op_implicit(v=AX.60)
ms:contentKeyID: 62204424
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.AddressDisplay.Implicit
dev_langs:
- CSharp
- C++
- VB
---

# Implicit Conversion (AddressDisplay to TemplateControl)

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
Public Shared Widening Operator CType ( _
    target As AddressDisplay _
) As TemplateControl
'Usage
Dim input As AddressDisplay
Dim output As TemplateControl

output = CType(input, TemplateControl)
```

``` csharp
public static implicit operator TemplateControl (
    AddressDisplay target
)
```

``` c++
static implicit operator TemplateControl^ (
    AddressDisplay^ target
)
```

#### Parameters

  - target  
    Type: [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.AddressDisplay](addressdisplay-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)  

#### Return Value

Type: [System.Web.UI.TemplateControl](https://technet.microsoft.com/en-us/library/2174ac61\(v=ax.60\))  
Returns [TemplateControl](https://technet.microsoft.com/en-us/library/2174ac61\(v=ax.60\)).  

## See Also

#### Reference

[AddressDisplay Class](addressdisplay-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)


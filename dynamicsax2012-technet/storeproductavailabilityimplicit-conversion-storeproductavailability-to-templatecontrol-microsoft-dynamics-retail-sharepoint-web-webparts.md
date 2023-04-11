---
title: StoreProductAvailability Implicit Conversion (StoreProductAvailability to TemplateControl) (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: Implicit Conversion (StoreProductAvailability to TemplateControl)
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.StoreProductAvailability.op_Implicit(Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.StoreProductAvailability)~System.Web.UI.TemplateControl
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.webparts.storeproductavailability.op_implicit(v=AX.60)
ms:contentKeyID: 62204626
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.StoreProductAvailability.Implicit
dev_langs:
- CSharp
- C++
- VB
---

# Implicit Conversion (StoreProductAvailability to TemplateControl)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
Public Shared Widening Operator CType ( _
    target As StoreProductAvailability _
) As TemplateControl
'Usage
Dim input As StoreProductAvailability
Dim output As TemplateControl

output = CType(input, TemplateControl)
```

``` csharp
public static implicit operator TemplateControl (
    StoreProductAvailability target
)
```

``` c++
static implicit operator TemplateControl^ (
    StoreProductAvailability^ target
)
```

#### Parameters

  - target  
    Type: [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.StoreProductAvailability](storeproductavailability-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)  

#### Return Value

Type: [System.Web.UI.TemplateControl](https://technet.microsoft.com/library/2174ac61\(v=ax.60\))  
Returns [TemplateControl](https://technet.microsoft.com/library/2174ac61\(v=ax.60\)).  

## See Also

#### Reference

[StoreProductAvailability Class](storeproductavailability-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)


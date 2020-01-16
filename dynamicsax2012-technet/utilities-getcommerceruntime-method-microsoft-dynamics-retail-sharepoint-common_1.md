---
title: Utilities.GetCommerceRuntime Method  (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: GetCommerceRuntime Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Common.Utilities.GetCommerceRuntime
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.common.utilities.getcommerceruntime(v=AX.60)
ms:contentKeyID: 62205396
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetCommerceRuntime Method

Gets the CommerceRuntime instance initialized by using the currently executing application's config.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Common](microsoft-dynamics-retail-sharepoint-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetCommerceRuntime As CommerceRuntime
'Usage
Dim returnValue As CommerceRuntime

returnValue = Utilities.GetCommerceRuntime()
```

``` csharp
public static CommerceRuntime GetCommerceRuntime()
```

``` c++
public:
static CommerceRuntime^ GetCommerceRuntime()
```

#### Return Value

Type: CommerceRuntime  
Commerce runtime instance.  

## Remarks

Caches the commerce runtime configuration and default channel identifier.

## See Also

#### Reference

[Utilities Class](utilities-class-microsoft-dynamics-retail-sharepoint-common.md)

[GetCommerceRuntime Overload](utilities-getcommerceruntime-method-microsoft-dynamics-retail-sharepoint-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)


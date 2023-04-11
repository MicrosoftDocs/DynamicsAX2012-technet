---
title: Utilities.GetCommerceRuntime Method (Configuration) (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: GetCommerceRuntime Method (Configuration)
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Common.Utilities.GetCommerceRuntime(System.Configuration.Configuration)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.common.utilities.getcommerceruntime(v=AX.60)
ms:contentKeyID: 62202587
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetCommerceRuntime Method (Configuration)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the CommerceRuntime instance initialized by using the provided application configuration.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Common](microsoft-dynamics-retail-sharepoint-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetCommerceRuntime ( _
    appConfiguration As Configuration _
) As CommerceRuntime
'Usage
Dim appConfiguration As Configuration
Dim returnValue As CommerceRuntime

returnValue = Utilities.GetCommerceRuntime(appConfiguration)
```

``` csharp
public static CommerceRuntime GetCommerceRuntime(
    Configuration appConfiguration
)
```

``` c++
public:
static CommerceRuntime^ GetCommerceRuntime(
    Configuration^ appConfiguration
)
```

#### Parameters

  - appConfiguration  
    Type: [System.Configuration.Configuration](https://technet.microsoft.com/library/s7kc101z\(v=ax.60\))  

#### Return Value

Type: CommerceRuntime  
Commerce runtime instance.  

## Remarks

Caches the default channel identifier.

## See Also

#### Reference

[Utilities Class](utilities-class-microsoft-dynamics-retail-sharepoint-common.md)

[GetCommerceRuntime Overload](utilities-getcommerceruntime-method-microsoft-dynamics-retail-sharepoint-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)


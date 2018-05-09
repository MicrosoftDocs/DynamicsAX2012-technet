---
title: FacebookSecurityTokenServiceConfiguration.Current Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Common)
TOCTitle: Current Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Common.FacebookSecurityTokenServiceConfiguration.Current
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.common.facebooksecuritytokenserviceconfiguration.current(v=AX.60)
ms:contentKeyID: 62202353
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Common.FacebookSecurityTokenServiceConfiguration.Current
dev_langs:
- CSharp
- C++
- VB
---

# Current Property

Provides a model for creating a single Configuration object for the application. The first call creates a new CustomSecruityTokenServiceConfiguration and places it into the current HttpApplicationState using the key "FacebookSecurityTokenServiceConfigurationKey". Subsequent calls will return the same Configuration object. This maintains any state that is set between calls and improves performance.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Common](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared ReadOnly Property Current As FacebookSecurityTokenServiceConfiguration
    Get
'Usage
Dim value As FacebookSecurityTokenServiceConfiguration

value = FacebookSecurityTokenServiceConfiguration.Current
```

``` csharp
public static FacebookSecurityTokenServiceConfiguration Current { get; }
```

``` c++
public:
static property FacebookSecurityTokenServiceConfiguration^ Current {
    FacebookSecurityTokenServiceConfiguration^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Common.FacebookSecurityTokenServiceConfiguration](facebooksecuritytokenserviceconfiguration-class-microsoft-dynamics-retail-sharepoint-web-common.md)  
Returns [FacebookSecurityTokenServiceConfiguration](facebooksecuritytokenserviceconfiguration-class-microsoft-dynamics-retail-sharepoint-web-common.md).  

## See Also

#### Reference

[FacebookSecurityTokenServiceConfiguration Class](facebooksecuritytokenserviceconfiguration-class-microsoft-dynamics-retail-sharepoint-web-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Common Namespace](microsoft-dynamics-retail-sharepoint-web-common-namespace.md)


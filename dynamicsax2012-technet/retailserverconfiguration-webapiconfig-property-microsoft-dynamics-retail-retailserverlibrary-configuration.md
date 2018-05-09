---
title: RetailServerConfiguration.WebApiConfig Property  (Microsoft.Dynamics.Retail.RetailServerLibrary.Configuration)
TOCTitle: WebApiConfig Property
ms:assetid: P:Microsoft.Dynamics.Retail.RetailServerLibrary.Configuration.RetailServerConfiguration.WebApiConfig
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.retailserverlibrary.configuration.retailserverconfiguration.webapiconfig(v=AX.60)
ms:contentKeyID: 62203064
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.Configuration.RetailServerConfiguration.WebApiConfig
dev_langs:
- CSharp
- C++
- VB
---

# WebApiConfig Property

Gets the Web API configuration object.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.Configuration](microsoft-dynamics-retail-retailserverlibrary-configuration-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Public Shared ReadOnly Property WebApiConfig As IWebApiConfig
    Get
'Usage
Dim value As IWebApiConfig

value = RetailServerConfiguration.WebApiConfig
```

``` csharp
public static IWebApiConfig WebApiConfig { get; }
```

``` c++
public:
static property IWebApiConfig^ WebApiConfig {
    IWebApiConfig^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.RetailServerLibrary.IWebApiConfig](iwebapiconfig-interface-microsoft-dynamics-retail-retailserverlibrary.md)  
Returns [IWebApiConfig](iwebapiconfig-interface-microsoft-dynamics-retail-retailserverlibrary.md).  

## See Also

#### Reference

[RetailServerConfiguration Class](retailserverconfiguration-class-microsoft-dynamics-retail-retailserverlibrary-configuration.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.Configuration Namespace](microsoft-dynamics-retail-retailserverlibrary-configuration-namespace.md)


---
title: DefaultWebApiConfig.Register Method  (Microsoft.Dynamics.Retail.RetailServerLibrary)
TOCTitle: Register Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.DefaultWebApiConfig.Register(System.Web.Http.HttpConfiguration)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.retailserverlibrary.defaultwebapiconfig.register(v=AX.60)
ms:contentKeyID: 62203687
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.DefaultWebApiConfig.Register
dev_langs:
- CSharp
- C++
- VB
---

# Register Method

Registration procedure.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary](microsoft-dynamics-retail-retailserverlibrary-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Public Overridable Sub Register ( _
    config As HttpConfiguration _
)
'Usage
Dim instance As DefaultWebApiConfig
Dim config As HttpConfiguration

instance.Register(config)
```

``` csharp
public virtual void Register(
    HttpConfiguration config
)
```

``` c++
public:
virtual void Register(
    HttpConfiguration^ config
)
```

#### Parameters

  - config  
    Type: HttpConfiguration  

#### Implements

[IWebApiConfig.Register(HttpConfiguration)](iwebapiconfig-register-method-microsoft-dynamics-retail-retailserverlibrary.md)  

## See Also

#### Reference

[DefaultWebApiConfig Class](defaultwebapiconfig-class-microsoft-dynamics-retail-retailserverlibrary.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary Namespace](microsoft-dynamics-retail-retailserverlibrary-namespace.md)


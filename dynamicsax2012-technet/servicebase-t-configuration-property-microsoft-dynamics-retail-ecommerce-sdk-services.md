---
title: ServiceBase(T).Configuration Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: Configuration Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ServiceBase`1.Configuration
ms:mtpsurl: https://technet.microsoft.com/library/Dn988598(v=AX.60)
ms:contentKeyID: 65318150
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ServiceBase`1.Configuration
dev_langs:
- CSharp
- C++
- VB
---

# Configuration Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Protected MustOverride ReadOnly Property Configuration As IConfiguration
    Get
'Usage
Dim value As IConfiguration

value = Me.Configuration
```

``` csharp
protected abstract IConfiguration Configuration { get; }
```

``` c++
protected:
virtual property IConfiguration^ Configuration {
    IConfiguration^ get () abstract;
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Storefront.IConfiguration](iconfiguration-interface-microsoft-dynamics-retail-ecommerce-sdk-core-storefront.md)  

## See Also

#### Reference

[ServiceBase\<T\> Class](servicebase-t-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)


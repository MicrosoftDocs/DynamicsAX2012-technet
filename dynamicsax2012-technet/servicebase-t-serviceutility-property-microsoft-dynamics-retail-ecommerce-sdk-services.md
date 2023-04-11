---
title: ServiceBase(T).ServiceUtility Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: ServiceUtility Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ServiceBase`1.ServiceUtility
ms:mtpsurl: https://technet.microsoft.com/library/Dn988195(v=AX.60)
ms:contentKeyID: 65317243
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ServiceBase`1.ServiceUtility
dev_langs:
- CSharp
- C++
- VB
---

# ServiceUtility Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Protected MustOverride ReadOnly Property ServiceUtility As ServiceUtilityBase
    Get
'Usage
Dim value As ServiceUtilityBase

value = Me.ServiceUtility
```

``` csharp
protected abstract ServiceUtilityBase ServiceUtility { get; }
```

``` c++
protected:
virtual property ServiceUtilityBase^ ServiceUtility {
    ServiceUtilityBase^ get () abstract;
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ServiceUtilityBase](serviceutilitybase-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[ServiceBase\<T\> Class](servicebase-t-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)


---
title: ServiceBase(T).SearchEngine Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: SearchEngine Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ServiceBase`1.SearchEngine
ms:mtpsurl: https://technet.microsoft.com/library/Dn998764(v=AX.60)
ms:contentKeyID: 65317449
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ServiceBase`1.SearchEngine
dev_langs:
- CSharp
- C++
- VB
---

# SearchEngine Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Protected MustOverride ReadOnly Property SearchEngine As ISearchEngine
    Get
'Usage
Dim value As ISearchEngine

value = Me.SearchEngine
```

``` csharp
protected abstract ISearchEngine SearchEngine { get; }
```

``` c++
protected:
virtual property ISearchEngine^ SearchEngine {
    ISearchEngine^ get () abstract;
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.ISearchEngine](isearchengine-interface-microsoft-dynamics-retail-ecommerce-sdk-core.md)  

## See Also

#### Reference

[ServiceBase\<T\> Class](servicebase-t-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)


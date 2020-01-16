---
title: ServiceBase(T).ProductValidator Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: ProductValidator Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ServiceBase`1.ProductValidator
ms:mtpsurl: https://technet.microsoft.com/library/Dn967114(v=AX.60)
ms:contentKeyID: 65318482
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ServiceBase`1.ProductValidator
dev_langs:
- CSharp
- C++
- VB
---

# ProductValidator Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Protected MustOverride ReadOnly Property ProductValidator As IProductValidator
    Get
'Usage
Dim value As IProductValidator

value = Me.ProductValidator
```

``` csharp
protected abstract IProductValidator ProductValidator { get; }
```

``` c++
protected:
virtual property IProductValidator^ ProductValidator {
    IProductValidator^ get () abstract;
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.IProductValidator](iproductvalidator-interface-microsoft-dynamics-retail-ecommerce-sdk-core.md)  

## See Also

#### Reference

[ServiceBase\<T\> Class](servicebase-t-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)


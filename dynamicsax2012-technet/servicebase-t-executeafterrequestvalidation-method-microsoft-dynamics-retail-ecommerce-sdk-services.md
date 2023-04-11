---
title: ServiceBase(T).ExecuteAfterRequestValidation Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: ExecuteAfterRequestValidation Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ServiceBase`1.ExecuteAfterRequestValidation(Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ServiceResponse,System.Action)
ms:mtpsurl: https://technet.microsoft.com/library/Dn998536(v=AX.60)
ms:contentKeyID: 65316969
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ServiceBase`1.ExecuteAfterRequestValidation
dev_langs:
- CSharp
- C++
- VB
---

# ExecuteAfterRequestValidation Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Protected MustOverride Sub ExecuteAfterRequestValidation ( _
    response As ServiceResponse, _
    action As Action _
)
'Usage
Dim response As ServiceResponse
Dim action As Action

Me.ExecuteAfterRequestValidation(response, _
    action)
```

``` csharp
protected abstract void ExecuteAfterRequestValidation(
    ServiceResponse response,
    Action action
)
```

``` c++
protected:
virtual void ExecuteAfterRequestValidation(
    ServiceResponse^ response, 
    Action^ action
) abstract
```

#### Parameters

  - response  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ServiceResponse](serviceresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

<!-- end list -->

  - action  
    Type: [System.Action](https://technet.microsoft.com/library/bb534741\(v=ax.60\))  

## See Also

#### Reference

[ServiceBase\<T\> Class](servicebase-t-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)


---
title: ServiceUtilityBase.GetShoppingCartIdFromPersistenceStorage Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: GetShoppingCartIdFromPersistenceStorage Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ServiceUtilityBase.GetShoppingCartIdFromPersistenceStorage(Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.SessionType)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.serviceutilitybase.getshoppingcartidfrompersistencestorage(v=AX.60)
ms:contentKeyID: 65318145
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ServiceUtilityBase.GetShoppingCartIdFromPersistenceStorage
dev_langs:
- CSharp
- C++
- VB
---

# GetShoppingCartIdFromPersistenceStorage Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Public MustOverride Function GetShoppingCartIdFromPersistenceStorage ( _
    sessionType As SessionType _
) As String
'Usage
Dim instance As ServiceUtilityBase
Dim sessionType As SessionType
Dim returnValue As String

returnValue = instance.GetShoppingCartIdFromPersistenceStorage(sessionType)
```

``` csharp
public abstract string GetShoppingCartIdFromPersistenceStorage(
    SessionType sessionType
)
```

``` c++
public:
virtual String^ GetShoppingCartIdFromPersistenceStorage(
    SessionType sessionType
) abstract
```

#### Parameters

  - sessionType  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.SessionType](sessiontype-enumeration-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ServiceUtilityBase Class](serviceutilitybase-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)


---
title: ServiceUtilityBase.GetCartIdFromPersistenceStorage Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: GetCartIdFromPersistenceStorage Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ServiceUtilityBase.GetCartIdFromPersistenceStorage(Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.SessionType,Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.CartType)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.serviceutilitybase.getcartidfrompersistencestorage(v=AX.60)
ms:contentKeyID: 65316391
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ServiceUtilityBase.GetCartIdFromPersistenceStorage
dev_langs:
- CSharp
- C++
- VB
---

# GetCartIdFromPersistenceStorage Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function GetCartIdFromPersistenceStorage ( _
    sessionType As SessionType, _
    cartType As CartType _
) As String
'Usage
Dim instance As ServiceUtilityBase
Dim sessionType As SessionType
Dim cartType As CartType
Dim returnValue As String

returnValue = instance.GetCartIdFromPersistenceStorage(sessionType, _
    cartType)
```

``` csharp
public virtual string GetCartIdFromPersistenceStorage(
    SessionType sessionType,
    CartType cartType
)
```

``` c++
public:
virtual String^ GetCartIdFromPersistenceStorage(
    SessionType sessionType, 
    CartType cartType
)
```

#### Parameters

  - sessionType  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.SessionType](sessiontype-enumeration-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

<!-- end list -->

  - cartType  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.CartType](carttype-enumeration-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ServiceUtilityBase Class](serviceutilitybase-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)


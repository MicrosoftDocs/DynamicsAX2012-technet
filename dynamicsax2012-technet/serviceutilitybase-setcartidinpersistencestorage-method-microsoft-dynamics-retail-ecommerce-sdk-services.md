---
title: ServiceUtilityBase.SetCartIdInPersistenceStorage Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: SetCartIdInPersistenceStorage Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ServiceUtilityBase.SetCartIdInPersistenceStorage(Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.SessionType,Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.CartType,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.serviceutilitybase.setcartidinpersistencestorage(v=AX.60)
ms:contentKeyID: 65318166
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ServiceUtilityBase.SetCartIdInPersistenceStorage
dev_langs:
- CSharp
- C++
- VB
---

# SetCartIdInPersistenceStorage Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Public MustOverride Sub SetCartIdInPersistenceStorage ( _
    sessionType As SessionType, _
    cartType As CartType, _
    cartId As String _
)
'Usage
Dim instance As ServiceUtilityBase
Dim sessionType As SessionType
Dim cartType As CartType
Dim cartId As String

instance.SetCartIdInPersistenceStorage(sessionType, _
    cartType, cartId)
```

``` csharp
public abstract void SetCartIdInPersistenceStorage(
    SessionType sessionType,
    CartType cartType,
    string cartId
)
```

``` c++
public:
virtual void SetCartIdInPersistenceStorage(
    SessionType sessionType, 
    CartType cartType, 
    String^ cartId
) abstract
```

#### Parameters

  - sessionType  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.SessionType](sessiontype-enumeration-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

<!-- end list -->

  - cartType  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.CartType](carttype-enumeration-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

<!-- end list -->

  - cartId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ServiceUtilityBase Class](serviceutilitybase-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)


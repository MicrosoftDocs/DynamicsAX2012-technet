---
title: IApplicationServiceV1.GetAndIncrementStoreSeed Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: GetAndIncrementStoreSeed Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IApplicationServiceV1.GetAndIncrementStoreSeed(Microsoft.Dynamics.Retail.Pos.Contracts.Services.NumberSequenceSeedType)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.iapplicationservicev1.getandincrementstoreseed(v=AX.60)
ms:contentKeyID: 47343935
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IApplicationServiceV1.GetAndIncrementStoreSeed
dev_langs:
- CSharp
- C++
- VB
---

# GetAndIncrementStoreSeed Method

Gets and increments the current store seed value for the type given.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function GetAndIncrementStoreSeed ( _
    type As NumberSequenceSeedType _
) As Long
'Usage
Dim instance As IApplicationServiceV1
Dim type As NumberSequenceSeedType
Dim returnValue As Long

returnValue = instance.GetAndIncrementStoreSeed(type)
```

``` csharp
long GetAndIncrementStoreSeed(
    NumberSequenceSeedType type
)
```

``` c++
long long GetAndIncrementStoreSeed(
    NumberSequenceSeedType type
)
```

#### Parameters

  - type  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.NumberSequenceSeedType](numbersequenceseedtype-enumeration-microsoft-dynamics-retail-pos-contracts-services.md)  

#### Return Value

Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  
The seed value.  

## See Also

#### Reference

[IApplicationServiceV1 Interface](iapplicationservicev1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)


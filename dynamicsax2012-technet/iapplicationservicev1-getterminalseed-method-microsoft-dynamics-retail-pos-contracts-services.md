---
title: IApplicationServiceV1.GetTerminalSeed Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: GetTerminalSeed Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IApplicationServiceV1.GetTerminalSeed(Microsoft.Dynamics.Retail.Pos.Contracts.Services.NumberSequenceSeedType)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.iapplicationservicev1.getterminalseed(v=AX.60)
ms:contentKeyID: 47343927
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IApplicationServiceV1.GetTerminalSeed
dev_langs:
- CSharp
- C++
- VB
---

# GetTerminalSeed Method

Gets the current terminal seed value for the type given.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function GetTerminalSeed ( _
    type As NumberSequenceSeedType _
) As Long
'Usage
Dim instance As IApplicationServiceV1
Dim type As NumberSequenceSeedType
Dim returnValue As Long

returnValue = instance.GetTerminalSeed(type)
```

``` csharp
long GetTerminalSeed(
    NumberSequenceSeedType type
)
```

``` c++
long long GetTerminalSeed(
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


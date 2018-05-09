---
title: ILogOnV1.VerifyOperationAccess Method (IPosTransaction, PosisOperations) (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: VerifyOperationAccess Method (IPosTransaction, PosisOperations)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILogOnV1.VerifyOperationAccess(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,Microsoft.Dynamics.Retail.Pos.Contracts.PosisOperations)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.ilogonv1.verifyoperationaccess(v=AX.60)
ms:contentKeyID: 49851139
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# VerifyOperationAccess Method (IPosTransaction, PosisOperations)

Verifies if the transaction operator has access for a given operation.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function VerifyOperationAccess ( _
    posTransaction As IPosTransaction, _
    operation As PosisOperations _
) As Boolean
'Usage
Dim instance As ILogOnV1
Dim posTransaction As IPosTransaction
Dim operation As PosisOperations
Dim returnValue As Boolean

returnValue = instance.VerifyOperationAccess(posTransaction, _
    operation)
```

``` csharp
bool VerifyOperationAccess(
    IPosTransaction posTransaction,
    PosisOperations operation
)
```

``` c++
bool VerifyOperationAccess(
    IPosTransaction^ posTransaction, 
    PosisOperations operation
)
```

#### Parameters

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - operation  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.PosisOperations](posisoperations-enumeration-microsoft-dynamics-retail-pos-contracts.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
True if operator has access, false other wise.  

## Remarks

Use this method when transaction is available.

## See Also

#### Reference

[ILogOnV1 Interface](ilogonv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[VerifyOperationAccess Overload](ilogonv1-verifyoperationaccess-method-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)


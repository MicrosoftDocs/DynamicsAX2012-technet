---
title: IApplicationV1.RunOperation Method (PosisOperations, Object, IPosTransaction) (Microsoft.Dynamics.Retail.Pos.Contracts)
TOCTitle: RunOperation Method (PosisOperations, Object, IPosTransaction)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.IApplicationV1.RunOperation(Microsoft.Dynamics.Retail.Pos.Contracts.PosisOperations,System.Object,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.iapplicationv1.runoperation(v=AX.60)
ms:contentKeyID: 47128263
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# RunOperation Method (PosisOperations, Object, IPosTransaction)

Runs a POS operation using the posTransaction passed in.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts](microsoft-dynamics-retail-pos-contracts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function RunOperation ( _
    operationID As PosisOperations, _
    extraInfo As Object, _
    posTransaction As IPosTransaction _
) As IPosTransaction
'Usage
Dim instance As IApplicationV1
Dim operationID As PosisOperations
Dim extraInfo As Object
Dim posTransaction As IPosTransaction
Dim returnValue As IPosTransaction

returnValue = instance.RunOperation(operationID, _
    extraInfo, posTransaction)
```

``` csharp
IPosTransaction RunOperation(
    PosisOperations operationID,
    Object extraInfo,
    IPosTransaction posTransaction
)
```

``` c++
IPosTransaction^ RunOperation(
    PosisOperations operationID, 
    Object^ extraInfo, 
    IPosTransaction^ posTransaction
)
```

#### Parameters

  - operationID  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.PosisOperations](posisoperations-enumeration-microsoft-dynamics-retail-pos-contracts.md)  

<!-- end list -->

  - extraInfo  
    Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  

<!-- end list -->

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
An updated POS transaction object.  

## See Also

#### Reference

[IApplicationV1 Interface](iapplicationv1-interface-microsoft-dynamics-retail-pos-contracts.md)

[RunOperation Overload](iapplicationv1-runoperation-method-microsoft-dynamics-retail-pos-contracts.md)

[Microsoft.Dynamics.Retail.Pos.Contracts Namespace](microsoft-dynamics-retail-pos-contracts-namespace.md)


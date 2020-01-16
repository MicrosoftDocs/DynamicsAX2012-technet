---
title: IBlankOperationsV1.BlankOperation Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: BlankOperation Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IBlankOperationsV1.BlankOperation(Microsoft.Dynamics.Retail.Pos.Contracts.BusinessObjects.IBlankOperationInfo,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iblankoperationsv1.blankoperation(v=AX.60)
ms:contentKeyID: 47344372
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IBlankOperationsV1.BlankOperation
dev_langs:
- CSharp
- C++
- VB
---

# BlankOperation Method

Blank operation handles custom operations.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub BlankOperation ( _
    operationInfo As IBlankOperationInfo, _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As IBlankOperationsV1
Dim operationInfo As IBlankOperationInfo
Dim posTransaction As IPosTransaction

instance.BlankOperation(operationInfo, _
    posTransaction)
```

``` csharp
void BlankOperation(
    IBlankOperationInfo operationInfo,
    IPosTransaction posTransaction
)
```

``` c++
void BlankOperation(
    IBlankOperationInfo^ operationInfo, 
    IPosTransaction^ posTransaction
)
```

#### Parameters

  - operationInfo  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessObjects.IBlankOperationInfo](iblankoperationinfo-interface-microsoft-dynamics-retail-pos-contracts-businessobjects.md)  

<!-- end list -->

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IBlankOperationsV1 Interface](iblankoperationsv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)


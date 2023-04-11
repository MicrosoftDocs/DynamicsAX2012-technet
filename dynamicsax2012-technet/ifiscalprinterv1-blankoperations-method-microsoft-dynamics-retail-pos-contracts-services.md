---
title: IFiscalPrinterV1.BlankOperations Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: BlankOperations Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.BlankOperations(Microsoft.Dynamics.Retail.Pos.Contracts.BusinessObjects.IBlankOperationInfo,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ifiscalprinterv1.blankoperations(v=AX.60)
ms:contentKeyID: 62202009
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.BlankOperations
dev_langs:
- CSharp
- C++
- VB
---

# BlankOperations Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Displays an alert message according operation id passed.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub BlankOperations ( _
    operationInfo As IBlankOperationInfo, _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As IFiscalPrinterV1
Dim operationInfo As IBlankOperationInfo
Dim posTransaction As IPosTransaction

instance.BlankOperations(operationInfo, _
    posTransaction)
```

``` csharp
void BlankOperations(
    IBlankOperationInfo operationInfo,
    IPosTransaction posTransaction
)
```

``` c++
void BlankOperations(
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

[IFiscalPrinterV1 Interface](ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)


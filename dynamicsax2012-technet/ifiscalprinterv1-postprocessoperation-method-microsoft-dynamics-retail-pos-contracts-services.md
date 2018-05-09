---
title: IFiscalPrinterV1.PostProcessOperation Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PostProcessOperation Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.PostProcessOperation(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,Microsoft.Dynamics.Retail.Pos.Contracts.PosisOperations)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.ifiscalprinterv1.postprocessoperation(v=AX.60)
ms:contentKeyID: 62205307
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.PostProcessOperation
dev_langs:
- CSharp
- C++
- VB
---

# PostProcessOperation Method

After the operation has been processed this trigger is called.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PostProcessOperation ( _
    posTransaction As IPosTransaction, _
    posisOperation As PosisOperations _
)
'Usage
Dim instance As IFiscalPrinterV1
Dim posTransaction As IPosTransaction
Dim posisOperation As PosisOperations

instance.PostProcessOperation(posTransaction, _
    posisOperation)
```

``` csharp
void PostProcessOperation(
    IPosTransaction posTransaction,
    PosisOperations posisOperation
)
```

``` c++
void PostProcessOperation(
    IPosTransaction^ posTransaction, 
    PosisOperations posisOperation
)
```

#### Parameters

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - posisOperation  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.PosisOperations](posisoperations-enumeration-microsoft-dynamics-retail-pos-contracts.md)  

## See Also

#### Reference

[IFiscalPrinterV1 Interface](ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)


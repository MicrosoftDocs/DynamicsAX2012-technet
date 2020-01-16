---
title: IFiscalPrinterV2.HasSameShiftId Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: HasSameShiftId Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV2.HasSameShiftId(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ifiscalprinterv2.hassameshiftid(v=AX.60)
ms:contentKeyID: 62204384
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV2.HasSameShiftId
dev_langs:
- CSharp
- C++
- VB
---

# HasSameShiftId Method

Checks if Fiscal printer shift id equals to POS one

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function HasSameShiftId ( _
    transaction As IRetailTransaction _
) As Nullable(Of Boolean)
'Usage
Dim instance As IFiscalPrinterV2
Dim transaction As IRetailTransaction
Dim returnValue As Nullable(Of Boolean)

returnValue = instance.HasSameShiftId(transaction)
```

``` csharp
Nullable<bool> HasSameShiftId(
    IRetailTransaction transaction
)
```

``` c++
Nullable<bool> HasSameShiftId(
    IRetailTransaction^ transaction
)
```

#### Parameters

  - transaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

#### Return Value

Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))\>  
Returns true if the fiscal printer shift id equals to POS shift id  

## See Also

#### Reference

[IFiscalPrinterV2 Interface](ifiscalprinterv2-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)


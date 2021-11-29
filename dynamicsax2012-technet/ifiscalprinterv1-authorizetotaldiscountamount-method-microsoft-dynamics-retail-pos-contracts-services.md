---
title: IFiscalPrinterV1.AuthorizeTotalDiscountAmount Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: AuthorizeTotalDiscountAmount Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.AuthorizeTotalDiscountAmount(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction,System.Decimal,System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ifiscalprinterv1.authorizetotaldiscountamount(v=AX.60)
ms:contentKeyID: 62203521
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.AuthorizeTotalDiscountAmount
dev_langs:
- CSharp
- C++
- VB
---

# AuthorizeTotalDiscountAmount Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Returns true if total discount amount is authorized.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function AuthorizeTotalDiscountAmount ( _
    retail As IRetailTransaction, _
    amountValue As Decimal, _
    maxAmountValue As Decimal _
) As Boolean
'Usage
Dim instance As IFiscalPrinterV1
Dim retail As IRetailTransaction
Dim amountValue As Decimal
Dim maxAmountValue As Decimal
Dim returnValue As Boolean

returnValue = instance.AuthorizeTotalDiscountAmount(retail, _
    amountValue, maxAmountValue)
```

``` csharp
bool AuthorizeTotalDiscountAmount(
    IRetailTransaction retail,
    decimal amountValue,
    decimal maxAmountValue
)
```

``` c++
bool AuthorizeTotalDiscountAmount(
    IRetailTransaction^ retail, 
    Decimal amountValue, 
    Decimal maxAmountValue
)
```

#### Parameters

  - retail  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - amountValue  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - maxAmountValue  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[IFiscalPrinterV1 Interface](ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)


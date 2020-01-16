---
title: IFiscalPrinterV1.PostLineDiscountPercent Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PostLineDiscountPercent Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.PostLineDiscountPercent(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ifiscalprinterv1.postlinediscountpercent(v=AX.60)
ms:contentKeyID: 62205786
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.PostLineDiscountPercent
dev_langs:
- CSharp
- C++
- VB
---

# PostLineDiscountPercent Method

Triggered after setting a line discount percent to the transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PostLineDiscountPercent ( _
    posTransaction As IPosTransaction, _
    lineId As Integer _
)
'Usage
Dim instance As IFiscalPrinterV1
Dim posTransaction As IPosTransaction
Dim lineId As Integer

instance.PostLineDiscountPercent(posTransaction, _
    lineId)
```

``` csharp
void PostLineDiscountPercent(
    IPosTransaction posTransaction,
    int lineId
)
```

``` c++
void PostLineDiscountPercent(
    IPosTransaction^ posTransaction, 
    int lineId
)
```

#### Parameters

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - lineId  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[IFiscalPrinterV1 Interface](ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)


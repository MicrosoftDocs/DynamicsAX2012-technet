---
title: IFiscalPrinterV1.PrePayment Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PrePayment Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.PrePayment(Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResult,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,System.Object,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.ifiscalprinterv1.prepayment(v=AX.60)
ms:contentKeyID: 62205791
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.PrePayment
dev_langs:
- CSharp
- C++
- VB
---

# PrePayment Method

Triggered prior to a payment.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PrePayment ( _
    preTriggerResult As IPreTriggerResult, _
    posTransaction As IPosTransaction, _
    posOperation As Object, _
    tenderId As String _
)
'Usage
Dim instance As IFiscalPrinterV1
Dim preTriggerResult As IPreTriggerResult
Dim posTransaction As IPosTransaction
Dim posOperation As Object
Dim tenderId As String

instance.PrePayment(preTriggerResult, _
    posTransaction, posOperation, tenderId)
```

``` csharp
void PrePayment(
    IPreTriggerResult preTriggerResult,
    IPosTransaction posTransaction,
    Object posOperation,
    string tenderId
)
```

``` c++
void PrePayment(
    IPreTriggerResult^ preTriggerResult, 
    IPosTransaction^ posTransaction, 
    Object^ posOperation, 
    String^ tenderId
)
```

#### Parameters

  - preTriggerResult  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResult](ipretriggerresult-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)  

<!-- end list -->

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - posOperation  
    Type: [System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  

<!-- end list -->

  - tenderId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[IFiscalPrinterV1 Interface](ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)


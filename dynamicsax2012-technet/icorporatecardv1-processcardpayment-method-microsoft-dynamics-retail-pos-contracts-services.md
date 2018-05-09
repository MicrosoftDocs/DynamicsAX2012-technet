---
title: ICorporateCardV1.ProcessCardPayment Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ProcessCardPayment Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICorporateCardV1.ProcessCardPayment(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfo,System.Decimal,System.Object)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.icorporatecardv1.processcardpayment(v=AX.60)
ms:contentKeyID: 47343862
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICorporateCardV1.ProcessCardPayment
dev_langs:
- CSharp
- C++
- VB
---

# ProcessCardPayment Method

Processes the card payment and adds a payment line to the sale.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub ProcessCardPayment ( _
    cardInfo As ICardInfo, _
    amount As Decimal, _
    posTransaction As Object _
)
'Usage
Dim instance As ICorporateCardV1
Dim cardInfo As ICardInfo
Dim amount As Decimal
Dim posTransaction As Object

instance.ProcessCardPayment(cardInfo, _
    amount, posTransaction)
```

``` csharp
void ProcessCardPayment(
    ICardInfo cardInfo,
    decimal amount,
    Object posTransaction
)
```

``` c++
void ProcessCardPayment(
    ICardInfo^ cardInfo, 
    Decimal amount, 
    Object^ posTransaction
)
```

#### Parameters

  - cardInfo  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfo](icardinfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - amount  
    Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - posTransaction  
    Type: [System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  

## Examples

    LSRetailPosis.ApplicationServices.ICorporateCard.ProcessCardPayment(cardInfo, paidAmount, this.posTransaction);

## See Also

#### Reference

[ICorporateCardV1 Interface](icorporatecardv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)


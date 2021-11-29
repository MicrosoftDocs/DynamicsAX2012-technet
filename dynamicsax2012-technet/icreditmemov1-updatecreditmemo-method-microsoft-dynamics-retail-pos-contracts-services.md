---
title: ICreditMemoV1.UpdateCreditMemo Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: UpdateCreditMemo Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICreditMemoV1.UpdateCreditMemo(System.String,System.Decimal,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICreditMemoTenderLineItem)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.icreditmemov1.updatecreditmemo(v=AX.60)
ms:contentKeyID: 47344425
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICreditMemoV1.UpdateCreditMemo
dev_langs:
- CSharp
- C++
- VB
---

# UpdateCreditMemo Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Updates credit memo, deducts the amount paid with the credit memo from the credit memo's balance at the head office.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub UpdateCreditMemo ( _
    creditMemoNumber As String, _
    amount As Decimal, _
    retailTransaction As IRetailTransaction, _
    creditMemoTenderLineItem As ICreditMemoTenderLineItem _
)
'Usage
Dim instance As ICreditMemoV1
Dim creditMemoNumber As String
Dim amount As Decimal
Dim retailTransaction As IRetailTransaction
Dim creditMemoTenderLineItem As ICreditMemoTenderLineItem

instance.UpdateCreditMemo(creditMemoNumber, _
    amount, retailTransaction, creditMemoTenderLineItem)
```

``` csharp
void UpdateCreditMemo(
    string creditMemoNumber,
    decimal amount,
    IRetailTransaction retailTransaction,
    ICreditMemoTenderLineItem creditMemoTenderLineItem
)
```

``` c++
void UpdateCreditMemo(
    String^ creditMemoNumber, 
    Decimal amount, 
    IRetailTransaction^ retailTransaction, 
    ICreditMemoTenderLineItem^ creditMemoTenderLineItem
)
```

#### Parameters

  - creditMemoNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - amount  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - retailTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - creditMemoTenderLineItem  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICreditMemoTenderLineItem](icreditmemotenderlineitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## Remarks

This method is triggered when a transaction that contains a credit memo payment is completed.

## See Also

#### Reference

[ICreditMemoV1 Interface](icreditmemov1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)


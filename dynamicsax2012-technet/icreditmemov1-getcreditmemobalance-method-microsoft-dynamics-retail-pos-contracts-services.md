---
title: ICreditMemoV1.GetCreditMemoBalance Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: GetCreditMemoBalance Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICreditMemoV1.GetCreditMemoBalance(System.String,System.Decimal@)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.icreditmemov1.getcreditmemobalance(v=AX.60)
ms:contentKeyID: 47343972
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICreditMemoV1.GetCreditMemoBalance
dev_langs:
- CSharp
- C++
- VB
---

# GetCreditMemoBalance Method

Gets credit memo balance, returns the balance of a credit memo.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub GetCreditMemoBalance ( _
    creditMemoNumber As String, _
    ByRef balance As Decimal _
)
'Usage
Dim instance As ICreditMemoV1
Dim creditMemoNumber As String
Dim balance As Decimal

instance.GetCreditMemoBalance(creditMemoNumber, _
    balance)
```

``` csharp
void GetCreditMemoBalance(
    string creditMemoNumber,
    ref decimal balance
)
```

``` c++
void GetCreditMemoBalance(
    String^ creditMemoNumber, 
    Decimal% balance
)
```

#### Parameters

  - creditMemoNumber  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - balance  
    Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  

## Remarks

This method is triggered by the "Credit memo balance" operation.

## See Also

#### Reference

[ICreditMemoV1 Interface](icreditmemov1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)


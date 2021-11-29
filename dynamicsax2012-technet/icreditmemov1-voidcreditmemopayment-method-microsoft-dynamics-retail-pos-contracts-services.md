---
title: ICreditMemoV1.VoidCreditMemoPayment Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: VoidCreditMemoPayment Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICreditMemoV1.VoidCreditMemoPayment(System.Boolean@,System.String@,System.String,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.icreditmemov1.voidcreditmemopayment(v=AX.60)
ms:contentKeyID: 47344231
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICreditMemoV1.VoidCreditMemoPayment
dev_langs:
- CSharp
- C++
- VB
---

# VoidCreditMemoPayment Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Voids credit memo payment, releases the credit memo at the head office.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub VoidCreditMemoPayment ( _
    ByRef voided As Boolean, _
    ByRef comment As String, _
    creditMemoNumber As String, _
    retailTransaction As IRetailTransaction _
)
'Usage
Dim instance As ICreditMemoV1
Dim voided As Boolean
Dim comment As String
Dim creditMemoNumber As String
Dim retailTransaction As IRetailTransaction

instance.VoidCreditMemoPayment(voided, _
    comment, creditMemoNumber, retailTransaction)
```

``` csharp
void VoidCreditMemoPayment(
    ref bool voided,
    ref string comment,
    string creditMemoNumber,
    IRetailTransaction retailTransaction
)
```

``` c++
void VoidCreditMemoPayment(
    bool% voided, 
    String^% comment, 
    String^ creditMemoNumber, 
    IRetailTransaction^ retailTransaction
)
```

#### Parameters

  - voided  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - comment  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - creditMemoNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - retailTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## Remarks

This method is triggered when a credit memo payment line is voided.

## See Also

#### Reference

[ICreditMemoV1 Interface](icreditmemov1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)


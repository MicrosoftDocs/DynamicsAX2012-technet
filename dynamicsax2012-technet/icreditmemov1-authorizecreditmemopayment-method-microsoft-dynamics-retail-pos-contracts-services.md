---
title: ICreditMemoV1.AuthorizeCreditMemoPayment Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: AuthorizeCreditMemoPayment Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICreditMemoV1.AuthorizeCreditMemoPayment(System.Boolean@,System.String@,System.String@,System.String@,System.Decimal@,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.icreditmemov1.authorizecreditmemopayment(v=AX.60)
ms:contentKeyID: 47344488
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICreditMemoV1.AuthorizeCreditMemoPayment
dev_langs:
- CSharp
- C++
- VB
---

# AuthorizeCreditMemoPayment Method

Authorizes payment with a credit memo.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub AuthorizeCreditMemoPayment ( _
    ByRef valid As Boolean, _
    ByRef comment As String, _
    ByRef creditMemoId As String, _
    ByRef currencyCode As String, _
    ByRef amount As Decimal, _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As ICreditMemoV1
Dim valid As Boolean
Dim comment As String
Dim creditMemoId As String
Dim currencyCode As String
Dim amount As Decimal
Dim posTransaction As IPosTransaction

instance.AuthorizeCreditMemoPayment(valid, _
    comment, creditMemoId, currencyCode, _
    amount, posTransaction)
```

``` csharp
void AuthorizeCreditMemoPayment(
    ref bool valid,
    ref string comment,
    ref string creditMemoId,
    ref string currencyCode,
    ref decimal amount,
    IPosTransaction posTransaction
)
```

``` c++
void AuthorizeCreditMemoPayment(
    bool% valid, 
    String^% comment, 
    String^% creditMemoId, 
    String^% currencyCode, 
    Decimal% amount, 
    IPosTransaction^ posTransaction
)
```

#### Parameters

  - valid  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - comment  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - creditMemoId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - amount  
    Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## Remarks

This method is triggered when a credit memo is used as payment.

## See Also

#### Reference

[ICreditMemoV1 Interface](icreditmemov1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)


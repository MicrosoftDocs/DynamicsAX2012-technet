---
title: ITransactionServicesV1.GetLoyaltyPointsStatus Method  (Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices)
TOCTitle: GetLoyaltyPointsStatus Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.GetLoyaltyPointsStatus(System.Boolean@,System.String@,System.Decimal@,System.Int32@,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.transactionservices.itransactionservicesv1.getloyaltypointsstatus(v=AX.60)
ms:contentKeyID: 47128374
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.GetLoyaltyPointsStatus
dev_langs:
- CSharp
- C++
- VB
---

# GetLoyaltyPointsStatus Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Note: This API is now obsolete.**

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<ObsoleteAttribute("This method has been deprecated. Use the ILoyalty::GetLoyaltyBalanceInfo method instead")> _
Sub GetLoyaltyPointsStatus ( _
    ByRef valid As Boolean, _
    ByRef comment As String, _
    ByRef points As Decimal, _
    ByRef loyaltyTenderTypeBase As Integer, _
    loyaltyCardNumber As String _
)
'Usage
Dim instance As ITransactionServicesV1
Dim valid As Boolean
Dim comment As String
Dim points As Decimal
Dim loyaltyTenderTypeBase As Integer
Dim loyaltyCardNumber As String

instance.GetLoyaltyPointsStatus(valid, _
    comment, points, loyaltyTenderTypeBase, _
    loyaltyCardNumber)
```

``` csharp
[ObsoleteAttribute("This method has been deprecated. Use the ILoyalty::GetLoyaltyBalanceInfo method instead")]
void GetLoyaltyPointsStatus(
    ref bool valid,
    ref string comment,
    ref decimal points,
    ref int loyaltyTenderTypeBase,
    string loyaltyCardNumber
)
```

``` c++
[ObsoleteAttribute(L"This method has been deprecated. Use the ILoyalty::GetLoyaltyBalanceInfo method instead")]
void GetLoyaltyPointsStatus(
    bool% valid, 
    String^% comment, 
    Decimal% points, 
    int% loyaltyTenderTypeBase, 
    String^ loyaltyCardNumber
)
```

#### Parameters

  - valid  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - comment  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - points  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - loyaltyTenderTypeBase  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

<!-- end list -->

  - loyaltyCardNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ITransactionServicesV1 Interface](itransactionservicesv1-interface-microsoft-dynamics-retail-pos-contracts-transactionservices.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices Namespace](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)


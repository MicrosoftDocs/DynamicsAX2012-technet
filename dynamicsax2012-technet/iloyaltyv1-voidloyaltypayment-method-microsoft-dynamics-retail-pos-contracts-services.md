---
title: ILoyaltyV1.VoidLoyaltyPayment Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: VoidLoyaltyPayment Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILoyaltyV1.VoidLoyaltyPayment(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyTenderLineItem)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.iloyaltyv1.voidloyaltypayment(v=AX.60)
ms:contentKeyID: 47343938
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILoyaltyV1.VoidLoyaltyPayment
dev_langs:
- CSharp
- C++
- VB
---

# VoidLoyaltyPayment Method

Called when a loyalty payment is being voided.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function VoidLoyaltyPayment ( _
    retailTransaction As IRetailTransaction, _
    loyaltyTenderItem As ILoyaltyTenderLineItem _
) As Boolean
'Usage
Dim instance As ILoyaltyV1
Dim retailTransaction As IRetailTransaction
Dim loyaltyTenderItem As ILoyaltyTenderLineItem
Dim returnValue As Boolean

returnValue = instance.VoidLoyaltyPayment(retailTransaction, _
    loyaltyTenderItem)
```

``` csharp
bool VoidLoyaltyPayment(
    IRetailTransaction retailTransaction,
    ILoyaltyTenderLineItem loyaltyTenderItem
)
```

``` c++
bool VoidLoyaltyPayment(
    IRetailTransaction^ retailTransaction, 
    ILoyaltyTenderLineItem^ loyaltyTenderItem
)
```

#### Parameters

  - retailTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - loyaltyTenderItem  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyTenderLineItem](iloyaltytenderlineitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
true if it is successful; otherwise, false.  

## See Also

#### Reference

[ILoyaltyV1 Interface](iloyaltyv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)


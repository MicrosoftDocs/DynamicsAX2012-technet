---
title: ILoyaltyItemV2.TenderType Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: TenderType Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyItemV2.TenderType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iloyaltyitemv2.tendertype(v=AX.60)
ms:contentKeyID: 62204284
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyItemV2.TenderType
dev_langs:
- CSharp
- C++
- VB
---

# TenderType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Tender type.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property TenderType As LoyaltyCardTenderType
    Get
    Set
'Usage
Dim instance As ILoyaltyItemV2
Dim value As LoyaltyCardTenderType

value = instance.TenderType

instance.TenderType = value
```

``` csharp
LoyaltyCardTenderType TenderType { get; set; }
```

``` c++
property LoyaltyCardTenderType TenderType {
    LoyaltyCardTenderType get ();
    void set (LoyaltyCardTenderType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.LoyaltyCardTenderType](loyaltycardtendertype-enumeration-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
Returns [LoyaltyCardTenderType](loyaltycardtendertype-enumeration-microsoft-dynamics-retail-pos-contracts-dataentity.md).  

## See Also

#### Reference

[ILoyaltyItemV2 Interface](iloyaltyitemv2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)


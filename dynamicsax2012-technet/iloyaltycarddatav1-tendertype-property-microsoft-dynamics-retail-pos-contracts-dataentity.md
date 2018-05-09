---
title: ILoyaltyCardDataV1.TenderType Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: TenderType Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyCardDataV1.TenderType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.iloyaltycarddatav1.tendertype(v=AX.60)
ms:contentKeyID: 62205194
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyCardDataV1.TenderType
dev_langs:
- CSharp
- C++
- VB
---

# TenderType Property

**Note: This API is now obsolete.**

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<ObsoleteAttribute("Not used any more.")> _
Property TenderType As LoyaltyTenderTypeBase
    Get
    Set
'Usage
Dim instance As ILoyaltyCardDataV1
Dim value As LoyaltyTenderTypeBase

value = instance.TenderType

instance.TenderType = value
```

``` csharp
[ObsoleteAttribute("Not used any more.")]
LoyaltyTenderTypeBase TenderType { get; set; }
```

``` c++
[ObsoleteAttribute(L"Not used any more.")]
property LoyaltyTenderTypeBase TenderType {
    LoyaltyTenderTypeBase get ();
    void set (LoyaltyTenderTypeBase value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.LoyaltyTenderTypeBase](loyaltytendertypebase-enumeration-microsoft-dynamics-retail-pos-contracts-services.md)  
Returns [LoyaltyTenderTypeBase](loyaltytendertypebase-enumeration-microsoft-dynamics-retail-pos-contracts-services.md).  

## See Also

#### Reference

[ILoyaltyCardDataV1 Interface](iloyaltycarddatav1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)


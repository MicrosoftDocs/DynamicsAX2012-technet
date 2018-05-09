---
title: ICardTenderLineItemV1.EFTInfo Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: EFTInfo Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardTenderLineItemV1.EFTInfo
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.icardtenderlineitemv1.eftinfo(v=AX.60)
ms:contentKeyID: 49842704
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardTenderLineItemV1.EFTInfo
dev_langs:
- CSharp
- C++
- VB
---

# EFTInfo Property

EFT information regarding the EFT transaction

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property EFTInfo As IEFTInfo
    Get
    Set
'Usage
Dim instance As ICardTenderLineItemV1
Dim value As IEFTInfo

value = instance.EFTInfo

instance.EFTInfo = value
```

``` csharp
IEFTInfo EFTInfo { get; set; }
```

``` c++
property IEFTInfo^ EFTInfo {
    IEFTInfo^ get ();
    void set (IEFTInfo^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfo](ieftinfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
Returns [IEFTInfo](ieftinfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md).  

## See Also

#### Reference

[ICardTenderLineItemV1 Interface](icardtenderlineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)


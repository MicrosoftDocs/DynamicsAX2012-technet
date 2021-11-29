---
title: ICorporateCardTenderLineItemV1.TemporaryCar Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: TemporaryCar Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICorporateCardTenderLineItemV1.TemporaryCar
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.icorporatecardtenderlineitemv1.temporarycar(v=AX.60)
ms:contentKeyID: 49844924
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICorporateCardTenderLineItemV1.TemporaryCar
dev_langs:
- CSharp
- C++
- VB
---

# TemporaryCar Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Is the vehicle being filled, a temporary member of the fleet?

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property TemporaryCar As Boolean
    Get
    Set
'Usage
Dim instance As ICorporateCardTenderLineItemV1
Dim value As Boolean

value = instance.TemporaryCar

instance.TemporaryCar = value
```

``` csharp
bool TemporaryCar { get; set; }
```

``` c++
property bool TemporaryCar {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ICorporateCardTenderLineItemV1 Interface](icorporatecardtenderlineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)


---
title: ICardTenderLineItemV1.CardName Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: CardName Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardTenderLineItemV1.CardName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.icardtenderlineitemv1.cardname(v=AX.60)
ms:contentKeyID: 49837508
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardTenderLineItemV1.CardName
dev_langs:
- CSharp
- C++
- VB
---

# CardName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The name of the card VISA,Maestro,JCB,etc.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property CardName As String
    Get
    Set
'Usage
Dim instance As ICardTenderLineItemV1
Dim value As String

value = instance.CardName

instance.CardName = value
```

``` csharp
string CardName { get; set; }
```

``` c++
property String^ CardName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ICardTenderLineItemV1 Interface](icardtenderlineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)


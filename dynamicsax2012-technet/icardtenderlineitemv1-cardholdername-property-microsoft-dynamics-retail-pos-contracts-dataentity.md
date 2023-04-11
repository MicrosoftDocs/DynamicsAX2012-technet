---
title: ICardTenderLineItemV1.CardHolderName Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: CardHolderName Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardTenderLineItemV1.CardHolderName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.icardtenderlineitemv1.cardholdername(v=AX.60)
ms:contentKeyID: 49837899
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardTenderLineItemV1.CardHolderName
dev_langs:
- CSharp
- C++
- VB
---

# CardHolderName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The name of the cardholder.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property CardHolderName As String
    Get
    Set
'Usage
Dim instance As ICardTenderLineItemV1
Dim value As String

value = instance.CardHolderName

instance.CardHolderName = value
```

``` csharp
string CardHolderName { get; set; }
```

``` c++
property String^ CardHolderName {
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


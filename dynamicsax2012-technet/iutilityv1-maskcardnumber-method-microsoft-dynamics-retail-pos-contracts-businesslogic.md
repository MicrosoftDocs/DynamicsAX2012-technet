---
title: IUtilityV1.MaskCardNumber Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: MaskCardNumber Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUtilityV1.MaskCardNumber(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.iutilityv1.maskcardnumber(v=AX.60)
ms:contentKeyID: 47129298
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUtilityV1.MaskCardNumber
dev_langs:
- CSharp
- C++
- VB
---

# MaskCardNumber Method

Mask the card numbers to last 4 digits.

Example card types used: Credit cards/Debit cards.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function MaskCardNumber ( _
    cardNumber As String _
) As String
'Usage
Dim instance As IUtilityV1
Dim cardNumber As String
Dim returnValue As String

returnValue = instance.MaskCardNumber(cardNumber)
```

``` csharp
string MaskCardNumber(
    string cardNumber
)
```

``` c++
String^ MaskCardNumber(
    String^ cardNumber
)
```

#### Parameters

  - cardNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Masked card number  

## See Also

#### Reference

[IUtilityV1 Interface](iutilityv1-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)


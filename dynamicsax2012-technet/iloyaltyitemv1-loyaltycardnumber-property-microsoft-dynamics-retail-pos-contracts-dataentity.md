---
title: ILoyaltyItemV1.LoyaltyCardNumber Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: LoyaltyCardNumber Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyItemV1.LoyaltyCardNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iloyaltyitemv1.loyaltycardnumber(v=AX.60)
ms:contentKeyID: 49820835
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyItemV1.LoyaltyCardNumber
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyCardNumber Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Loyalty card number.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property LoyaltyCardNumber As String
    Get
    Set
'Usage
Dim instance As ILoyaltyItemV1
Dim value As String

value = instance.LoyaltyCardNumber

instance.LoyaltyCardNumber = value
```

``` csharp
string LoyaltyCardNumber { get; set; }
```

``` c++
property String^ LoyaltyCardNumber {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ILoyaltyItemV1 Interface](iloyaltyitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)


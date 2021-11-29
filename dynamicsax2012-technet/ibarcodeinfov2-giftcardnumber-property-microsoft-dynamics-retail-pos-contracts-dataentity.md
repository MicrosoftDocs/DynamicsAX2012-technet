---
title: IBarcodeInfoV2.GiftCardNumber Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: GiftCardNumber Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBarcodeInfoV2.GiftCardNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ibarcodeinfov2.giftcardnumber(v=AX.60)
ms:contentKeyID: 49854894
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBarcodeInfoV2.GiftCardNumber
dev_langs:
- CSharp
- C++
- VB
---

# GiftCardNumber Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the gift card number.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property GiftCardNumber As String
    Get
    Set
'Usage
Dim instance As IBarcodeInfoV2
Dim value As String

value = instance.GiftCardNumber

instance.GiftCardNumber = value
```

``` csharp
string GiftCardNumber { get; set; }
```

``` c++
property String^ GiftCardNumber {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[IBarcodeInfoV2 Interface](ibarcodeinfov2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)


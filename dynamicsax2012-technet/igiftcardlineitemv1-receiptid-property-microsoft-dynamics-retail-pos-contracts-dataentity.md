---
title: IGiftCardLineItemV1.ReceiptId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ReceiptId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IGiftCardLineItemV1.ReceiptId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.igiftcardlineitemv1.receiptid(v=AX.60)
ms:contentKeyID: 49824853
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IGiftCardLineItemV1.ReceiptId
dev_langs:
- CSharp
- C++
- VB
---

# ReceiptId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Get or set receipt id for this line item.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property ReceiptId As String
    Get
    Set
'Usage
Dim instance As IGiftCardLineItemV1
Dim value As String

value = instance.ReceiptId

instance.ReceiptId = value
```

``` csharp
string ReceiptId { get; set; }
```

``` c++
property String^ ReceiptId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[IGiftCardLineItemV1 Interface](igiftcardlineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)


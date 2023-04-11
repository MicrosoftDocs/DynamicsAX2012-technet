---
title: Cart.ReceiptTransactionTypeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReceiptTransactionTypeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.ReceiptTransactionTypeValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cart.receipttransactiontypevalue(v=AX.60)
ms:contentKeyID: 65322350
author: tfehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.ReceiptTransactionTypeValue
dev_langs:
- CSharp
- C++
- VB
---

# ReceiptTransactionTypeValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ReadOnlyAttribute("ReceiptTransactionTypeValue")> _
Public Property ReceiptTransactionTypeValue As Integer
    Get
    Set
'Usage
Dim instance As Cart
Dim value As Integer

value = instance.ReceiptTransactionTypeValue

instance.ReceiptTransactionTypeValue = value
```

``` csharp
[DataMemberAttribute]
[ReadOnlyAttribute("ReceiptTransactionTypeValue")]
public int ReceiptTransactionTypeValue { get; set; }
```

``` c++
[DataMemberAttribute]
[ReadOnlyAttribute(L"ReceiptTransactionTypeValue")]
public:
property int ReceiptTransactionTypeValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[Cart Class](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


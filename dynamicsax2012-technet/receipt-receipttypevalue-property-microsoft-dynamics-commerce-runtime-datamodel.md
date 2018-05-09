---
title: Receipt.ReceiptTypeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReceiptTypeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Receipt.ReceiptTypeValue
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.receipt.receipttypevalue(v=AX.60)
ms:contentKeyID: 62214671
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Receipt.ReceiptTypeValue
dev_langs:
- CSharp
- C++
- VB
---

# ReceiptTypeValue Property

Gets or sets the value of the ReceiptType enum. Used by OData only.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ReceiptTypeValue As Integer
    Get
    Set
'Usage
Dim instance As Receipt
Dim value As Integer

value = instance.ReceiptTypeValue

instance.ReceiptTypeValue = value
```

``` csharp
[DataMemberAttribute]
public int ReceiptTypeValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int ReceiptTypeValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[Receipt Class](receipt-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


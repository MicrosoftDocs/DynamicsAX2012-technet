---
title: KitTransaction.KitTransactionLines Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: KitTransactionLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.KitTransaction.KitTransactionLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.kittransaction.kittransactionlines(v=AX.60)
ms:contentKeyID: 62209554
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.KitTransaction.KitTransactionLines
dev_langs:
- CSharp
- C++
- VB
---

# KitTransactionLines Property

Gets or sets the kit transaction lines.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property KitTransactionLines As ICollection(Of KitTransactionLine)
    Get
    Set
'Usage
Dim instance As KitTransaction
Dim value As ICollection(Of KitTransactionLine)

value = instance.KitTransactionLines

instance.KitTransactionLines = value
```

``` csharp
[DataMemberAttribute]
public ICollection<KitTransactionLine> KitTransactionLines { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<KitTransactionLine^>^ KitTransactionLines {
    ICollection<KitTransactionLine^>^ get ();
    void set (ICollection<KitTransactionLine^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[KitTransactionLine](kittransactionline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ICollection\<T\>](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\)).  

## See Also

#### Reference

[KitTransaction Class](kittransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


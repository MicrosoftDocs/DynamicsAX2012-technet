---
title: ReceiptMask.IsIndependent Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsIndependent Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptMask.IsIndependent
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.receiptmask.isindependent(v=AX.60)
ms:contentKeyID: 62210155
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptMask.IsIndependent
dev_langs:
- CSharp
- C++
- VB
---

# IsIndependent Property

Gets a value indicating whether the receipt mask is independent.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ISINDEPENDENT")> _
<DataMemberAttribute> _
Public Property IsIndependent As Boolean
    Get
    Friend Set
'Usage
Dim instance As ReceiptMask
Dim value As Boolean

value = instance.IsIndependent
```

``` csharp
[ColumnAttribute("ISINDEPENDENT")]
[DataMemberAttribute]
public bool IsIndependent { get; internal set; }
```

``` c++
[ColumnAttribute(L"ISINDEPENDENT")]
[DataMemberAttribute]
public:
property bool IsIndependent {
    bool get ();
    internal: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ReceiptMask Class](receiptmask-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


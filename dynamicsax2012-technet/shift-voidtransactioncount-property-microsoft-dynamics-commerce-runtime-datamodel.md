---
title: Shift.VoidTransactionCount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: VoidTransactionCount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.VoidTransactionCount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shift.voidtransactioncount(v=AX.60)
ms:contentKeyID: 62210514
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.VoidTransactionCount
dev_langs:
- CSharp
- C++
- VB
---

# VoidTransactionCount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets count of void transactions.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("VOIDSCOUNT")> _
<DataMemberAttribute> _
Public Property VoidTransactionCount As Integer
    Get
    Set
'Usage
Dim instance As Shift
Dim value As Integer

value = instance.VoidTransactionCount

instance.VoidTransactionCount = value
```

``` csharp
[ColumnAttribute("VOIDSCOUNT")]
[DataMemberAttribute]
public int VoidTransactionCount { get; set; }
```

``` c++
[ColumnAttribute(L"VOIDSCOUNT")]
[DataMemberAttribute]
public:
property int VoidTransactionCount {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[Shift Class](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


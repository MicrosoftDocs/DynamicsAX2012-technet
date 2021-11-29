---
title: ShiftTenderLine.Count Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Count Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.Count
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shifttenderline.count(v=AX.60)
ms:contentKeyID: 62212364
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.Count
dev_langs:
- CSharp
- C++
- VB
---

# Count Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets count of transactions.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("COUNT")> _
Public Property Count As Integer
    Get
    Set
'Usage
Dim instance As ShiftTenderLine
Dim value As Integer

value = instance.Count

instance.Count = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("COUNT")]
public int Count { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"COUNT")]
public:
property int Count {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[ShiftTenderLine Class](shifttenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


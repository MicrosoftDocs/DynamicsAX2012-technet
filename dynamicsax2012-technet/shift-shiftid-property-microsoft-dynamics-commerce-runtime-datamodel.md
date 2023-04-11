---
title: Shift.ShiftId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ShiftId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.ShiftId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shift.shiftid(v=AX.60)
ms:contentKeyID: 62213347
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.ShiftId
dev_langs:
- CSharp
- C++
- VB
---

# ShiftId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the shift id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<KeyAttribute> _
<ColumnAttribute("SHIFTID")> _
<DataMemberAttribute> _
Public Property ShiftId As Long
    Get
    Set
'Usage
Dim instance As Shift
Dim value As Long

value = instance.ShiftId

instance.ShiftId = value
```

``` csharp
[KeyAttribute]
[ColumnAttribute("SHIFTID")]
[DataMemberAttribute]
public long ShiftId { get; set; }
```

``` c++
[KeyAttribute]
[ColumnAttribute(L"SHIFTID")]
[DataMemberAttribute]
public:
property long long ShiftId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[Shift Class](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


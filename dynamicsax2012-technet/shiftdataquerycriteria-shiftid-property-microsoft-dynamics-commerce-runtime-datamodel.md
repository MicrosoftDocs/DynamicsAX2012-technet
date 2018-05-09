---
title: ShiftDataQueryCriteria.ShiftId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ShiftId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftDataQueryCriteria.ShiftId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.shiftdataquerycriteria.shiftid(v=AX.60)
ms:contentKeyID: 65322084
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftDataQueryCriteria.ShiftId
dev_langs:
- CSharp
- C++
- VB
---

# ShiftId Property

Gets or sets the shift identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ShiftId As Nullable(Of Long)
    Get
    Set
'Usage
Dim instance As ShiftDataQueryCriteria
Dim value As Nullable(Of Long)

value = instance.ShiftId

instance.ShiftId = value
```

``` csharp
[DataMemberAttribute]
public Nullable<long> ShiftId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Nullable<long long> ShiftId {
    Nullable<long long> get ();
    void set (Nullable<long long> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))\>  
Returns [Nullable\<T\>](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\)).  

## See Also

#### Reference

[ShiftDataQueryCriteria Class](shiftdataquerycriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


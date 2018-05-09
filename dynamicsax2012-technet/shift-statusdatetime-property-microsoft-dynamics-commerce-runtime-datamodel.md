---
title: Shift.StatusDateTime Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: StatusDateTime Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.StatusDateTime
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.shift.statusdatetime(v=AX.60)
ms:contentKeyID: 62215242
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.StatusDateTime
dev_langs:
- CSharp
- C++
- VB
---

# StatusDateTime Property

Gets or sets current status's date/time.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("STATUSDATETIMEUTC")> _
<RequiredToBeUtcAttribute(False)> _
<DataMemberAttribute> _
Public Property StatusDateTime As Nullable(Of DateTimeOffset)
    Get
    Set
'Usage
Dim instance As Shift
Dim value As Nullable(Of DateTimeOffset)

value = instance.StatusDateTime

instance.StatusDateTime = value
```

``` csharp
[ColumnAttribute("STATUSDATETIMEUTC")]
[RequiredToBeUtcAttribute(false)]
[DataMemberAttribute]
public Nullable<DateTimeOffset> StatusDateTime { get; set; }
```

``` c++
[ColumnAttribute(L"STATUSDATETIMEUTC")]
[RequiredToBeUtcAttribute(false)]
[DataMemberAttribute]
public:
property Nullable<DateTimeOffset> StatusDateTime {
    Nullable<DateTimeOffset> get ();
    void set (Nullable<DateTimeOffset> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\))\<[DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\))\>  
Returns [Nullable\<T\>](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\)).  

## See Also

#### Reference

[Shift Class](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


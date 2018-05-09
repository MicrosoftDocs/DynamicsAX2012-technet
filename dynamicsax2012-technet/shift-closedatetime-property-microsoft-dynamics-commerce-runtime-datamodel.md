---
title: Shift.CloseDateTime Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CloseDateTime Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.CloseDateTime
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.shift.closedatetime(v=AX.60)
ms:contentKeyID: 62211234
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.CloseDateTime
dev_langs:
- CSharp
- C++
- VB
---

# CloseDateTime Property

Gets or sets close date/time of Shift in channel timezone.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CLOSEDATETIMEUTC")> _
<DataMemberAttribute> _
<RequiredToBeUtcAttribute(False)> _
Public Property CloseDateTime As Nullable(Of DateTimeOffset)
    Get
    Set
'Usage
Dim instance As Shift
Dim value As Nullable(Of DateTimeOffset)

value = instance.CloseDateTime

instance.CloseDateTime = value
```

``` csharp
[ColumnAttribute("CLOSEDATETIMEUTC")]
[DataMemberAttribute]
[RequiredToBeUtcAttribute(false)]
public Nullable<DateTimeOffset> CloseDateTime { get; set; }
```

``` c++
[ColumnAttribute(L"CLOSEDATETIMEUTC")]
[DataMemberAttribute]
[RequiredToBeUtcAttribute(false)]
public:
property Nullable<DateTimeOffset> CloseDateTime {
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


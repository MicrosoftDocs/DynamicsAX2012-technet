---
title: Shift.StartDateTime Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: StartDateTime Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.StartDateTime
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shift.startdatetime(v=AX.60)
ms:contentKeyID: 62212599
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.StartDateTime
dev_langs:
- CSharp
- C++
- VB
---

# StartDateTime Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets start date/time of Shift in channel timezone.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<RequiredToBeUtcAttribute(False)> _
<DataMemberAttribute> _
<ColumnAttribute("STARTDATETIMEUTC")> _
Public Property StartDateTime As Nullable(Of DateTimeOffset)
    Get
    Set
'Usage
Dim instance As Shift
Dim value As Nullable(Of DateTimeOffset)

value = instance.StartDateTime

instance.StartDateTime = value
```

``` csharp
[RequiredToBeUtcAttribute(false)]
[DataMemberAttribute]
[ColumnAttribute("STARTDATETIMEUTC")]
public Nullable<DateTimeOffset> StartDateTime { get; set; }
```

``` c++
[RequiredToBeUtcAttribute(false)]
[DataMemberAttribute]
[ColumnAttribute(L"STARTDATETIMEUTC")]
public:
property Nullable<DateTimeOffset> StartDateTime {
    Nullable<DateTimeOffset> get ();
    void set (Nullable<DateTimeOffset> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))\>  
Returns [Nullable\<T\>](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\)).  

## See Also

#### Reference

[Shift Class](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


---
title: EmployeeActivitySearchCriteria.ToDateTimeOffset Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ToDateTimeOffset Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivitySearchCriteria.ToDateTimeOffset
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.employeeactivitysearchcriteria.todatetimeoffset(v=AX.60)
ms:contentKeyID: 62212462
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivitySearchCriteria.ToDateTimeOffset
dev_langs:
- CSharp
- C++
- VB
---

# ToDateTimeOffset Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the To date and time offset in channel's local time zone.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ToDateTimeOffset As Nullable(Of DateTimeOffset)
    Get
    Set
'Usage
Dim instance As EmployeeActivitySearchCriteria
Dim value As Nullable(Of DateTimeOffset)

value = instance.ToDateTimeOffset

instance.ToDateTimeOffset = value
```

``` csharp
[DataMemberAttribute]
public Nullable<DateTimeOffset> ToDateTimeOffset { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Nullable<DateTimeOffset> ToDateTimeOffset {
    Nullable<DateTimeOffset> get ();
    void set (Nullable<DateTimeOffset> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))\>  
Returns [Nullable\<T\>](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\)).  

## See Also

#### Reference

[EmployeeActivitySearchCriteria Class](employeeactivitysearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


---
title: EmployeeActivitySearchCriteria.FromDateTimeOffset Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: FromDateTimeOffset Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivitySearchCriteria.FromDateTimeOffset
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.employeeactivitysearchcriteria.fromdatetimeoffset(v=AX.60)
ms:contentKeyID: 62210164
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivitySearchCriteria.FromDateTimeOffset
dev_langs:
- CSharp
- C++
- VB
---

# FromDateTimeOffset Property

Gets or sets the From date and time offset in channel's local time zone.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property FromDateTimeOffset As Nullable(Of DateTimeOffset)
    Get
    Set
'Usage
Dim instance As EmployeeActivitySearchCriteria
Dim value As Nullable(Of DateTimeOffset)

value = instance.FromDateTimeOffset

instance.FromDateTimeOffset = value
```

``` csharp
[DataMemberAttribute]
public Nullable<DateTimeOffset> FromDateTimeOffset { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Nullable<DateTimeOffset> FromDateTimeOffset {
    Nullable<DateTimeOffset> get ();
    void set (Nullable<DateTimeOffset> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\))\<[DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\))\>  
Returns [Nullable\<T\>](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\)).  

## See Also

#### Reference

[EmployeeActivitySearchCriteria Class](employeeactivitysearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


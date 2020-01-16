---
title: EmployeeActivity.ActivityDateTimeOffset Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ActivityDateTimeOffset Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivity.ActivityDateTimeOffset
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.employeeactivity.activitydatetimeoffset(v=AX.60)
ms:contentKeyID: 62214909
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivity.ActivityDateTimeOffset
dev_langs:
- CSharp
- C++
- VB
---

# ActivityDateTimeOffset Property

Gets or sets the activity date and time offset in UTC time zone.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("REGDATETIME")> _
<RequiredToBeUtcAttribute(True)> _
<DataMemberAttribute> _
Public Property ActivityDateTimeOffset As Nullable(Of DateTimeOffset)
    Get
    Set
'Usage
Dim instance As EmployeeActivity
Dim value As Nullable(Of DateTimeOffset)

value = instance.ActivityDateTimeOffset

instance.ActivityDateTimeOffset = value
```

``` csharp
[ColumnAttribute("REGDATETIME")]
[RequiredToBeUtcAttribute(true)]
[DataMemberAttribute]
public Nullable<DateTimeOffset> ActivityDateTimeOffset { get; set; }
```

``` c++
[ColumnAttribute(L"REGDATETIME")]
[RequiredToBeUtcAttribute(true)]
[DataMemberAttribute]
public:
property Nullable<DateTimeOffset> ActivityDateTimeOffset {
    Nullable<DateTimeOffset> get ();
    void set (Nullable<DateTimeOffset> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))\>  
Returns [Nullable\<T\>](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\)).  

## See Also

#### Reference

[EmployeeActivity Class](employeeactivity-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


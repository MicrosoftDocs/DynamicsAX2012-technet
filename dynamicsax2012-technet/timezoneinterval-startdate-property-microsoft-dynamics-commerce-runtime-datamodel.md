---
title: TimeZoneInterval.StartDate Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: StartDate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TimeZoneInterval.StartDate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.timezoneinterval.startdate(v=AX.60)
ms:contentKeyID: 65317552
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TimeZoneInterval.StartDate
dev_langs:
- CSharp
- C++
- VB
---

# StartDate Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the start date.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("STARTDATE")> _
<DataMemberAttribute> _
Public Property StartDate As DateTime
    Get
    Set
'Usage
Dim instance As TimeZoneInterval
Dim value As DateTime

value = instance.StartDate

instance.StartDate = value
```

``` csharp
[ColumnAttribute("STARTDATE")]
[DataMemberAttribute]
public DateTime StartDate { get; set; }
```

``` c++
[ColumnAttribute(L"STARTDATE")]
[DataMemberAttribute]
public:
property DateTime StartDate {
    DateTime get ();
    void set (DateTime value);
}
```

#### Property Value

Type: [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))  
Returns [DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\)).  

## See Also

#### Reference

[TimeZoneInterval Class](timezoneinterval-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


---
title: TimeZoneInterval.TimeSpanInMinutes Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TimeSpanInMinutes Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TimeZoneInterval.TimeSpanInMinutes
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.timezoneinterval.timespaninminutes(v=AX.60)
ms:contentKeyID: 65320373
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TimeZoneInterval.TimeSpanInMinutes
dev_langs:
- CSharp
- C++
- VB
---

# TimeSpanInMinutes Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the time span in minutes.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TIMESPANINMINUTES")> _
Public Property TimeSpanInMinutes As Integer
    Get
    Set
'Usage
Dim instance As TimeZoneInterval
Dim value As Integer

value = instance.TimeSpanInMinutes

instance.TimeSpanInMinutes = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TIMESPANINMINUTES")]
public int TimeSpanInMinutes { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TIMESPANINMINUTES")]
public:
property int TimeSpanInMinutes {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## Remarks

Please note, AX stores the offset in reverse value, e.g. -7 hours equals to 420 minutes.

## See Also

#### Reference

[TimeZoneInterval Class](timezoneinterval-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


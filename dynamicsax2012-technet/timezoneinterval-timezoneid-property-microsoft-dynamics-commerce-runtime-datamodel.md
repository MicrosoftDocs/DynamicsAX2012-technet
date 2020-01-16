---
title: TimeZoneInterval.TimeZoneId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TimeZoneId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TimeZoneInterval.TimeZoneId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.timezoneinterval.timezoneid(v=AX.60)
ms:contentKeyID: 65320130
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TimeZoneInterval.TimeZoneId
dev_langs:
- CSharp
- C++
- VB
---

# TimeZoneId Property

Gets or sets the time zone name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TIMEZONEID")> _
<DataMemberAttribute> _
Public Property TimeZoneId As String
    Get
    Set
'Usage
Dim instance As TimeZoneInterval
Dim value As String

value = instance.TimeZoneId

instance.TimeZoneId = value
```

``` csharp
[ColumnAttribute("TIMEZONEID")]
[DataMemberAttribute]
public string TimeZoneId { get; set; }
```

``` c++
[ColumnAttribute(L"TIMEZONEID")]
[DataMemberAttribute]
public:
property String^ TimeZoneId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TimeZoneInterval Class](timezoneinterval-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


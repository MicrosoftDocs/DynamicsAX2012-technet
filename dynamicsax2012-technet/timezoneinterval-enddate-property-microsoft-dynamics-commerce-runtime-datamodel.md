---
title: TimeZoneInterval.EndDate Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EndDate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TimeZoneInterval.EndDate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.timezoneinterval.enddate(v=AX.60)
ms:contentKeyID: 65320488
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TimeZoneInterval.EndDate
dev_langs:
- CSharp
- C++
- VB
---

# EndDate Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the end date.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ENDDATE")> _
Public Property EndDate As DateTime
    Get
    Set
'Usage
Dim instance As TimeZoneInterval
Dim value As DateTime

value = instance.EndDate

instance.EndDate = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ENDDATE")]
public DateTime EndDate { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ENDDATE")]
public:
property DateTime EndDate {
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


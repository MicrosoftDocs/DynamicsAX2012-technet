---
title: TimeZoneExtensions.GetTimeSpan Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GetTimeSpan Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.TimeZoneExtensions.GetTimeSpan(System.Collections.Generic.List{Microsoft.Dynamics.Commerce.Runtime.DataModel.TimeZoneInterval},System.DateTime)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.timezoneextensions.gettimespan(v=AX.60)
ms:contentKeyID: 65322759
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TimeZoneExtensions.GetTimeSpan
dev_langs:
- CSharp
- C++
- VB
---

# GetTimeSpan Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets time span for the given channel's date/time.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Function GetTimeSpan ( _
    timezoneRecords As List(Of TimeZoneInterval), _
    dateTime As DateTime _
) As TimeSpan
'Usage
Dim timezoneRecords As List(Of TimeZoneInterval)
Dim dateTime As DateTime
Dim returnValue As TimeSpan

returnValue = timezoneRecords.GetTimeSpan(dateTime)
```

``` csharp
public static TimeSpan GetTimeSpan(
    this List<TimeZoneInterval> timezoneRecords,
    DateTime dateTime
)
```

``` c++
[ExtensionAttribute]
public:
static TimeSpan GetTimeSpan(
    List<TimeZoneInterval^>^ timezoneRecords, 
    DateTime dateTime
)
```

#### Parameters

  - timezoneRecords  
    Type: [System.Collections.Generic.List](https://technet.microsoft.com/library/6sh2ey19\(v=ax.60\))\<[TimeZoneInterval](timezoneinterval-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - dateTime  
    Type: [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))  

#### Return Value

Type: [System.TimeSpan](https://technet.microsoft.com/library/269ew577\(v=ax.60\))  
The time zone offset.  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [List](https://technet.microsoft.com/library/6sh2ey19\(v=ax.60\))\<[TimeZoneInterval](timezoneinterval-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[TimeZoneExtensions Class](timezoneextensions-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


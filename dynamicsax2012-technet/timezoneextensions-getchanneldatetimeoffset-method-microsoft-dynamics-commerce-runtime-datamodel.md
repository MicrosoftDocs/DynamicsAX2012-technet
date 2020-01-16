---
title: TimeZoneExtensions.GetChannelDateTimeOffset Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GetChannelDateTimeOffset Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.TimeZoneExtensions.GetChannelDateTimeOffset(System.Collections.Generic.List{Microsoft.Dynamics.Commerce.Runtime.DataModel.TimeZoneInterval},System.DateTimeOffset)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.timezoneextensions.getchanneldatetimeoffset(v=AX.60)
ms:contentKeyID: 65319675
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TimeZoneExtensions.GetChannelDateTimeOffset
dev_langs:
- CSharp
- C++
- VB
---

# GetChannelDateTimeOffset Method

Converts to the channel's date/time.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Function GetChannelDateTimeOffset ( _
    timezoneRecords As List(Of TimeZoneInterval), _
    dateTimeOffset As DateTimeOffset _
) As DateTimeOffset
'Usage
Dim timezoneRecords As List(Of TimeZoneInterval)
Dim dateTimeOffset As DateTimeOffset
Dim returnValue As DateTimeOffset

returnValue = timezoneRecords.GetChannelDateTimeOffset(dateTimeOffset)
```

``` csharp
public static DateTimeOffset GetChannelDateTimeOffset(
    this List<TimeZoneInterval> timezoneRecords,
    DateTimeOffset dateTimeOffset
)
```

``` c++
[ExtensionAttribute]
public:
static DateTimeOffset GetChannelDateTimeOffset(
    List<TimeZoneInterval^>^ timezoneRecords, 
    DateTimeOffset dateTimeOffset
)
```

#### Parameters

  - timezoneRecords  
    Type: [System.Collections.Generic.List](https://technet.microsoft.com/library/6sh2ey19\(v=ax.60\))\<[TimeZoneInterval](timezoneinterval-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - dateTimeOffset  
    Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  

#### Return Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  
The time zone offset.  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [List](https://technet.microsoft.com/library/6sh2ey19\(v=ax.60\))\<[TimeZoneInterval](timezoneinterval-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[TimeZoneExtensions Class](timezoneextensions-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


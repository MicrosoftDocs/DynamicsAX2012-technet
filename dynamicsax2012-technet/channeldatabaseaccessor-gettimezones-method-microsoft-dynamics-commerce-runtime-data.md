---
title: ChannelDatabaseAccessor.GetTimeZones Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetTimeZones Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDatabaseAccessor.GetTimeZones(System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.channeldatabaseaccessor.gettimezones(v=AX.60)
ms:contentKeyID: 65319461
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDatabaseAccessor.GetTimeZones
dev_langs:
- CSharp
- C++
- VB
---

# GetTimeZones Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetTimeZones ( _
    timeZoneCode As Integer _
) As List(Of TimeZoneInterval)
'Usage
Dim instance As ChannelDatabaseAccessor
Dim timeZoneCode As Integer
Dim returnValue As List(Of TimeZoneInterval)

returnValue = instance.GetTimeZones(timeZoneCode)
```

``` csharp
public List<TimeZoneInterval> GetTimeZones(
    int timeZoneCode
)
```

``` c++
public:
List<TimeZoneInterval^>^ GetTimeZones(
    int timeZoneCode
)
```

#### Parameters

  - timeZoneCode  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

#### Return Value

Type: [System.Collections.Generic.List](https://technet.microsoft.com/library/6sh2ey19\(v=ax.60\))\<[TimeZoneInterval](timezoneinterval-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ChannelDatabaseAccessor Class](channeldatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


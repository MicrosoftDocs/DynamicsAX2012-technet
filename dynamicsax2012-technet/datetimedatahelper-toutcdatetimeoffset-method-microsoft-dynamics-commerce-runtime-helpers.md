---
title: DateTimeDataHelper.ToUtcDateTimeOffset Method  (Microsoft.Dynamics.Commerce.Runtime.Helpers)
TOCTitle: ToUtcDateTimeOffset Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Helpers.DateTimeDataHelper.ToUtcDateTimeOffset(System.Nullable{System.DateTime})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.helpers.datetimedatahelper.toutcdatetimeoffset(v=AX.60)
ms:contentKeyID: 62203503
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Helpers.DateTimeDataHelper.ToUtcDateTimeOffset
dev_langs:
- CSharp
- C++
- VB
---

# ToUtcDateTimeOffset Method

Converts the input date and time in UTC time zone to UTC date and time offset.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Helpers](microsoft-dynamics-commerce-runtime-helpers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Function ToUtcDateTimeOffset ( _
    utcDateTime As Nullable(Of DateTime) _
) As Nullable(Of DateTimeOffset)
'Usage
Dim utcDateTime As Nullable(Of DateTime)
Dim returnValue As Nullable(Of DateTimeOffset)

returnValue = utcDateTime.ToUtcDateTimeOffset()
```

``` csharp
public static Nullable<DateTimeOffset> ToUtcDateTimeOffset(
    this Nullable<DateTime> utcDateTime
)
```

``` c++
[ExtensionAttribute]
public:
static Nullable<DateTimeOffset> ToUtcDateTimeOffset(
    Nullable<DateTime> utcDateTime
)
```

#### Parameters

  - utcDateTime  
    Type: [System.Nullable](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\))\<[DateTime](https://technet.microsoft.com/en-us/library/03ybds8y\(v=ax.60\))\>  

#### Return Value

Type: [System.Nullable](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\))\<[DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\))\>  
The DateTimeOffset value; null, if the utcDateTime is null.  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [Nullable](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\))\<[DateTime](https://technet.microsoft.com/en-us/library/03ybds8y\(v=ax.60\))\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[DateTimeDataHelper Class](datetimedatahelper-class-microsoft-dynamics-commerce-runtime-helpers.md)

[Microsoft.Dynamics.Commerce.Runtime.Helpers Namespace](microsoft-dynamics-commerce-runtime-helpers-namespace.md)


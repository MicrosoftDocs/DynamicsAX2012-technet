---
title: DateTimeDataHelper.GetUtcDateTime Method  (Microsoft.Dynamics.Commerce.Runtime.Helpers)
TOCTitle: GetUtcDateTime Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Helpers.DateTimeDataHelper.GetUtcDateTime(System.Nullable{System.DateTimeOffset})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.helpers.datetimedatahelper.getutcdatetime(v=AX.60)
ms:contentKeyID: 62202823
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Helpers.DateTimeDataHelper.GetUtcDateTime
dev_langs:
- CSharp
- C++
- VB
---

# GetUtcDateTime Method

Gets the date and time in UTC from date and time offset.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Helpers](microsoft-dynamics-commerce-runtime-helpers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Function GetUtcDateTime ( _
    dateTimeOffset As Nullable(Of DateTimeOffset) _
) As Nullable(Of DateTime)
'Usage
Dim dateTimeOffset As Nullable(Of DateTimeOffset)
Dim returnValue As Nullable(Of DateTime)

returnValue = dateTimeOffset.GetUtcDateTime()
```

``` csharp
public static Nullable<DateTime> GetUtcDateTime(
    this Nullable<DateTimeOffset> dateTimeOffset
)
```

``` c++
[ExtensionAttribute]
public:
static Nullable<DateTime> GetUtcDateTime(
    Nullable<DateTimeOffset> dateTimeOffset
)
```

#### Parameters

  - dateTimeOffset  
    Type: [System.Nullable](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\))\<[DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\))\>  

#### Return Value

Type: [System.Nullable](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\))\<[DateTime](https://technet.microsoft.com/en-us/library/03ybds8y\(v=ax.60\))\>  
The DateTime value; null, if the dateTimeOffset is null.  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [Nullable](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\))\<[DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\))\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[DateTimeDataHelper Class](datetimedatahelper-class-microsoft-dynamics-commerce-runtime-helpers.md)

[Microsoft.Dynamics.Commerce.Runtime.Helpers Namespace](microsoft-dynamics-commerce-runtime-helpers-namespace.md)


---
title: RequestContextExtensions.ConvertDateTimeToChannelDate Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: ConvertDateTimeToChannelDate Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.RequestContextExtensions.ConvertDateTimeToChannelDate(Microsoft.Dynamics.Commerce.Runtime.RequestContext,System.DateTimeOffset)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.requestcontextextensions.convertdatetimetochanneldate(v=AX.60)
ms:contentKeyID: 65316354
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.RequestContextExtensions.ConvertDateTimeToChannelDate
dev_langs:
- CSharp
- C++
- VB
---

# ConvertDateTimeToChannelDate Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a [DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\)) object that is set to the current date and time on the current computer, with the offset set to the channel time's offset from Coordinated Universal Time (UTC).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Function ConvertDateTimeToChannelDate ( _
    requestContext As RequestContext, _
    dateTimeOffset As DateTimeOffset _
) As DateTimeOffset
'Usage
Dim requestContext As RequestContext
Dim dateTimeOffset As DateTimeOffset
Dim returnValue As DateTimeOffset

returnValue = requestContext.ConvertDateTimeToChannelDate(dateTimeOffset)
```

``` csharp
public static DateTimeOffset ConvertDateTimeToChannelDate(
    this RequestContext requestContext,
    DateTimeOffset dateTimeOffset
)
```

``` c++
[ExtensionAttribute]
public:
static DateTimeOffset ConvertDateTimeToChannelDate(
    RequestContext^ requestContext, 
    DateTimeOffset dateTimeOffset
)
```

#### Parameters

  - requestContext  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - dateTimeOffset  
    Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  

#### Return Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  
Instance of [DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\)) representing current date and time in channel time zone.  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[RequestContextExtensions Class](requestcontextextensions-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)


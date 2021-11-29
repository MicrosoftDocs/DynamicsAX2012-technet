---
title: DatabaseContext.ChannelDateTimeNow Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: ChannelDateTimeNow Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseContext.ChannelDateTimeNow
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.databasecontext.channeldatetimenow(v=AX.60)
ms:contentKeyID: 65315611
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseContext.ChannelDateTimeNow
dev_langs:
- CSharp
- C++
- VB
---

# ChannelDateTimeNow Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets current channel date/time.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property ChannelDateTimeNow As DateTimeOffset
    Get
'Usage
Dim instance As DatabaseContext
Dim value As DateTimeOffset

value = instance.ChannelDateTimeNow
```

``` csharp
public DateTimeOffset ChannelDateTimeNow { get; }
```

``` c++
public:
property DateTimeOffset ChannelDateTimeNow {
    DateTimeOffset get ();
}
```

#### Property Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  
Returns [DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\)).  

## See Also

#### Reference

[DatabaseContext Class](databasecontext-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


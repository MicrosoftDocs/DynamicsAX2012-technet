---
title: RowVersionHelper.Increment Method  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite)
TOCTitle: Increment Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.RowVersionHelper.Increment(System.Byte[])
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.sqlite.rowversionhelper.increment(v=AX.60)
ms:contentKeyID: 65319222
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.RowVersionHelper.Increment
dev_langs:
- CSharp
- C++
- VB
---

# Increment Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite](microsoft-dynamics-commerce-runtime-dataservices-sqlite-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.dll)

## Syntax

``` vb
'Declaration
Public Shared Function Increment ( _
    rowversion As Byte() _
) As Byte()
'Usage
Dim rowversion As Byte()
Dim returnValue As Byte()

returnValue = RowVersionHelper.Increment(rowversion)
```

``` csharp
public static byte[] Increment(
    byte[] rowversion
)
```

``` c++
public:
static array<unsigned char>^ Increment(
    array<unsigned char>^ rowversion
)
```

#### Parameters

  - rowversion  
    Type: [System.Byte](https://technet.microsoft.com/library/yyb1w04y\(v=ax.60\))\[\]  

#### Return Value

Type: [System.Byte](https://technet.microsoft.com/library/yyb1w04y\(v=ax.60\))\[\]  

## See Also

#### Reference

[RowVersionHelper Class](rowversionhelper-class-microsoft-dynamics-commerce-runtime-dataservices-sqlite.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite Namespace](microsoft-dynamics-commerce-runtime-dataservices-sqlite-namespace.md)


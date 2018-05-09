---
title: RowVersionHelper.AreEquals Method  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite)
TOCTitle: AreEquals Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.RowVersionHelper.AreEquals(System.Byte[],System.Byte[])
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.sqlite.rowversionhelper.areequals(v=AX.60)
ms:contentKeyID: 65320334
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.RowVersionHelper.AreEquals
dev_langs:
- CSharp
- C++
- VB
---

# AreEquals Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite](microsoft-dynamics-commerce-runtime-dataservices-sqlite-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.dll)

## Syntax

``` vb
'Declaration
Public Shared Function AreEquals ( _
    a As Byte(), _
    b As Byte() _
) As Boolean
'Usage
Dim a As Byte()
Dim b As Byte()
Dim returnValue As Boolean

returnValue = RowVersionHelper.AreEquals(a, b)
```

``` csharp
public static bool AreEquals(
    byte[] a,
    byte[] b
)
```

``` c++
public:
static bool AreEquals(
    array<unsigned char>^ a, 
    array<unsigned char>^ b
)
```

#### Parameters

  - a  
    Type: [System.Byte](https://technet.microsoft.com/en-us/library/yyb1w04y\(v=ax.60\))\[\]  

<!-- end list -->

  - b  
    Type: [System.Byte](https://technet.microsoft.com/en-us/library/yyb1w04y\(v=ax.60\))\[\]  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[RowVersionHelper Class](rowversionhelper-class-microsoft-dynamics-commerce-runtime-dataservices-sqlite.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite Namespace](microsoft-dynamics-commerce-runtime-dataservices-sqlite-namespace.md)


---
title: DataCacheAccessor.GenerateKey(T1, T2, T3, T4, T5, T6, T7, T8, T9) Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GenerateKey(T1, T2, T3, T4, T5, T6, T7, T8, T9) Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DataCacheAccessor.GenerateKey``9(System.String,``0,``1,``2,``3,``4,``5,``6,``7,``8)
ms:mtpsurl: https://technet.microsoft.com/library/Dn989803(v=AX.60)
ms:contentKeyID: 65320260
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DataCacheAccessor.GenerateKey``9
dev_langs:
- CSharp
- C++
- VB
---

# GenerateKey(T1, T2, T3, T4, T5, T6, T7, T8, T9) Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Generates a key, given a calling function name and the specified parameter hash.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Protected Overridable Function GenerateKey(Of T1, T2, T3, T4, T5, T6, T7, T8, T9) ( _
    callingFunction As String, _
    parameter1 As T1, _
    parameter2 As T2, _
    parameter3 As T3, _
    parameter4 As T4, _
    parameter5 As T5, _
    parameter6 As T6, _
    parameter7 As T7, _
    parameter8 As T8, _
    parameter9 As T9 _
) As String
'Usage
Dim callingFunction As String
Dim parameter1 As T1
Dim parameter2 As T2
Dim parameter3 As T3
Dim parameter4 As T4
Dim parameter5 As T5
Dim parameter6 As T6
Dim parameter7 As T7
Dim parameter8 As T8
Dim parameter9 As T9
Dim returnValue As String

returnValue = Me.GenerateKey(callingFunction, _
    parameter1, parameter2, parameter3, _
    parameter4, parameter5, parameter6, _
    parameter7, parameter8, parameter9)
```

``` csharp
protected virtual string GenerateKey<T1, T2, T3, T4, T5, T6, T7, T8, T9>(
    string callingFunction,
    T1 parameter1,
    T2 parameter2,
    T3 parameter3,
    T4 parameter4,
    T5 parameter5,
    T6 parameter6,
    T7 parameter7,
    T8 parameter8,
    T9 parameter9
)
```

``` c++
protected:
generic<typename T1, typename T2, typename T3, typename T4, typename T5, typename T6, typename T7, typename T8, typename T9>
virtual String^ GenerateKey(
    String^ callingFunction, 
    T1 parameter1, 
    T2 parameter2, 
    T3 parameter3, 
    T4 parameter4, 
    T5 parameter5, 
    T6 parameter6, 
    T7 parameter7, 
    T8 parameter8, 
    T9 parameter9
)
```

#### Type Parameters

  - T1

<!-- end list -->

  - T2

<!-- end list -->

  - T3

<!-- end list -->

  - T4

<!-- end list -->

  - T5

<!-- end list -->

  - T6

<!-- end list -->

  - T7

<!-- end list -->

  - T8

<!-- end list -->

  - T9

#### Parameters

  - callingFunction  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - parameter1  
    Type: T1  

<!-- end list -->

  - parameter2  
    Type: T2  

<!-- end list -->

  - parameter3  
    Type: T3  

<!-- end list -->

  - parameter4  
    Type: T4  

<!-- end list -->

  - parameter5  
    Type: T5  

<!-- end list -->

  - parameter6  
    Type: T6  

<!-- end list -->

  - parameter7  
    Type: T7  

<!-- end list -->

  - parameter8  
    Type: T8  

<!-- end list -->

  - parameter9  
    Type: T9  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The key matching this function call.  

## See Also

#### Reference

[DataCacheAccessor Class](datacacheaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


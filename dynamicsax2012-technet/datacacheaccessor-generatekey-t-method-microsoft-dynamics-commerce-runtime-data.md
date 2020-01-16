---
title: DataCacheAccessor.GenerateKey(T) Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GenerateKey(T) Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DataCacheAccessor.GenerateKey``1(System.String,``0)
ms:mtpsurl: https://technet.microsoft.com/library/Dn990456(v=AX.60)
ms:contentKeyID: 65321396
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DataCacheAccessor.GenerateKey``1
dev_langs:
- CSharp
- C++
- VB
---

# GenerateKey(T) Method

Generates a key, given a calling function name and the specified parameter hash.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Protected Overridable Function GenerateKey(Of T) ( _
    callingFunction As String, _
    parameterHash As T _
) As String
'Usage
Dim callingFunction As String
Dim parameterHash As T
Dim returnValue As String

returnValue = Me.GenerateKey(callingFunction, _
    parameterHash)
```

``` csharp
protected virtual string GenerateKey<T>(
    string callingFunction,
    T parameterHash
)
```

``` c++
protected:
generic<typename T>
virtual String^ GenerateKey(
    String^ callingFunction, 
    T parameterHash
)
```

#### Type Parameters

  - T

#### Parameters

  - callingFunction  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - parameterHash  
    Type: T  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The key matching this function call.  

## See Also

#### Reference

[DataCacheAccessor Class](datacacheaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


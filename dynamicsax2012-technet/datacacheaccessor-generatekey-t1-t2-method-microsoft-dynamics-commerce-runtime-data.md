---
title: DataCacheAccessor.GenerateKey(T1, T2) Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GenerateKey(T1, T2) Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DataCacheAccessor.GenerateKey``2(System.String,``0,``1)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn990756(v=AX.60)
ms:contentKeyID: 65321694
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DataCacheAccessor.GenerateKey``2
dev_langs:
- CSharp
- C++
- VB
---

# GenerateKey(T1, T2) Method

Generates a key, given a calling function name and the specified parameter hash.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Protected Overridable Function GenerateKey(Of T1, T2) ( _
    callingFunction As String, _
    parameter1 As T1, _
    parameter2 As T2 _
) As String
'Usage
Dim callingFunction As String
Dim parameter1 As T1
Dim parameter2 As T2
Dim returnValue As String

returnValue = Me.GenerateKey(callingFunction, _
    parameter1, parameter2)
```

``` csharp
protected virtual string GenerateKey<T1, T2>(
    string callingFunction,
    T1 parameter1,
    T2 parameter2
)
```

``` c++
protected:
generic<typename T1, typename T2>
virtual String^ GenerateKey(
    String^ callingFunction, 
    T1 parameter1, 
    T2 parameter2
)
```

#### Type Parameters

  - T1

<!-- end list -->

  - T2

#### Parameters

  - callingFunction  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - parameter1  
    Type: T1  

<!-- end list -->

  - parameter2  
    Type: T2  

#### Return Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The key matching this function call.  

## See Also

#### Reference

[DataCacheAccessor Class](datacacheaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


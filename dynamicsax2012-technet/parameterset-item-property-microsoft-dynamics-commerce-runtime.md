---
title: ParameterSet.Item Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: Item Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.ParameterSet.Item(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.parameterset.item(v=AX.60)
ms:contentKeyID: 49842394
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ParameterSet.Item
dev_langs:
- CSharp
- C++
- VB
---

# Item Property

Gets or sets the value associated with the specified key.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Overridable Property Item ( _
    key As String _
) As Object
    Get
    Set
'Usage
Dim instance As ParameterSet
Dim key As String
Dim value As Object

value = instance.Item(key)

instance.Item(key) = value
```

``` csharp
public virtual Object this[
    string key
] { get; set; }
```

``` c++
public:
virtual property Object^ Item[String^ key] {
    Object^ get (String^ key);
    void set (String^ key, Object^ value);
}
```

#### Parameters

  - key  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Property Value

Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
The value associated with the specified key or NULL if the specified key does not exist.  

## See Also

#### Reference

[ParameterSet Class](parameterset-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)


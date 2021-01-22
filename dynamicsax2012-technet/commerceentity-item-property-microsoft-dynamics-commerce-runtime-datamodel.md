---
title: CommerceEntity.Item Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Item Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity.Item(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.commerceentity.item(v=AX.60)
ms:contentKeyID: 49822966
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity.Item
dev_langs:
- CSharp
- C++
- VB
---

# Item Property

Gets or sets the value associated with the specified key.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property Item ( _
    key As String _
) As Object
    Get
    Set
'Usage
Dim instance As CommerceEntity
Dim key As String
Dim value As Object

value = instance.Item(key)

instance.Item(key) = value
```

``` csharp
public Object this[
    string key
] { get; set; }
```

``` c++
public:
property Object^ Item[String^ key] {
    Object^ get (String^ key);
    void set (String^ key, Object^ value);
}
```

#### Parameters

  - key  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Property Value

Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
The value stored for the specified key.  

## See Also

#### Reference

[CommerceEntity Class](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


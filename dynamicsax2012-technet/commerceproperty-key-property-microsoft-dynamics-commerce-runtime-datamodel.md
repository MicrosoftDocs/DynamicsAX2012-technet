---
title: CommerceProperty.Key Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Key Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceProperty.Key
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.commerceproperty.key(v=AX.60)
ms:contentKeyID: 62214444
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceProperty.Key
dev_langs:
- CSharp
- C++
- VB
---

# Key Property

Gets or sets the property key.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Key As String
    Get
    Set
'Usage
Dim instance As CommerceProperty
Dim value As String

value = instance.Key

instance.Key = value
```

``` csharp
[DataMemberAttribute]
public string Key { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Key {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[CommerceProperty Class](commerceproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


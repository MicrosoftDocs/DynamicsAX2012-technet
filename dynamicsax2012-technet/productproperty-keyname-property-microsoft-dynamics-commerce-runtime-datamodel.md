---
title: ProductProperty.KeyName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: KeyName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductProperty.KeyName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productproperty.keyname(v=AX.60)
ms:contentKeyID: 62207744
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductProperty.KeyName
dev_langs:
- CSharp
- C++
- VB
---

# KeyName Property

Gets or sets the name of the key.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property KeyName As String
    Get
    Set
'Usage
Dim instance As ProductProperty
Dim value As String

value = instance.KeyName

instance.KeyName = value
```

``` csharp
[DataMemberAttribute]
public string KeyName { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ KeyName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The name of the key.  

## See Also

#### Reference

[ProductProperty Class](productproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


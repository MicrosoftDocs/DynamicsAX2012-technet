---
title: Product.IsRemote Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsRemote Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.IsRemote
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.product.isremote(v=AX.60)
ms:contentKeyID: 62213178
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.IsRemote
dev_langs:
- CSharp
- C++
- VB
---

# IsRemote Property

Gets a value indicating whether this product was loaded from a remote data source.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<RequiredAttribute> _
<DataMemberAttribute> _
Public Property IsRemote As Boolean
    Get
    Set
'Usage
Dim instance As Product
Dim value As Boolean

value = instance.IsRemote

instance.IsRemote = value
```

``` csharp
[RequiredAttribute]
[DataMemberAttribute]
public bool IsRemote { get; set; }
```

``` c++
[RequiredAttribute]
[DataMemberAttribute]
public:
property bool IsRemote {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[Product Class](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


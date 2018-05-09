---
title: Product.IsKit Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsKit Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.IsKit
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.product.iskit(v=AX.60)
ms:contentKeyID: 62208117
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.IsKit
dev_langs:
- CSharp
- C++
- VB
---

# IsKit Property

Gets a value indicating whether this is a kit product or not.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<RequiredAttribute> _
<DataMemberAttribute> _
Public Property IsKit As Boolean
    Get
    Set
'Usage
Dim instance As Product
Dim value As Boolean

value = instance.IsKit

instance.IsKit = value
```

``` csharp
[RequiredAttribute]
[DataMemberAttribute]
public bool IsKit { get; set; }
```

``` c++
[RequiredAttribute]
[DataMemberAttribute]
public:
property bool IsKit {
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


---
title: Product.ParentKits Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ParentKits Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.ParentKits
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.product.parentkits(v=AX.60)
ms:contentKeyID: 65317842
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.ParentKits
dev_langs:
- CSharp
- C++
- VB
---

# ParentKits Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Property ParentKits As ICollection(Of KitComponent)
    Get
    Private Set
'Usage
Dim instance As Product
Dim value As ICollection(Of KitComponent)

value = instance.ParentKits
```

``` csharp
public ICollection<KitComponent> ParentKits { get; private set; }
```

``` c++
public:
property ICollection<KitComponent^>^ ParentKits {
    ICollection<KitComponent^>^ get ();
    private: void set (ICollection<KitComponent^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[KitComponent](kitcomponent-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[Product Class](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


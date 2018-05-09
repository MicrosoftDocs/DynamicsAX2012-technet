---
title: Product.AddParentKits Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AddParentKits Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.AddParentKits(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.KitComponent})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.product.addparentkits(v=AX.60)
ms:contentKeyID: 65321475
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.AddParentKits
dev_langs:
- CSharp
- C++
- VB
---

# AddParentKits Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub AddParentKits ( _
    kitComponents As IEnumerable(Of KitComponent) _
)
'Usage
Dim instance As Product
Dim kitComponents As IEnumerable(Of KitComponent)

instance.AddParentKits(kitComponents)
```

``` csharp
public void AddParentKits(
    IEnumerable<KitComponent> kitComponents
)
```

``` c++
public:
void AddParentKits(
    IEnumerable<KitComponent^>^ kitComponents
)
```

#### Parameters

  - kitComponents  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[KitComponent](kitcomponent-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[Product Class](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


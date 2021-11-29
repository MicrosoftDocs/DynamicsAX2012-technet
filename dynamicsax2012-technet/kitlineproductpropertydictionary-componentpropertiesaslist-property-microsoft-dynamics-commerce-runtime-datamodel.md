---
title: KitLineProductPropertyDictionary.ComponentPropertiesAsList Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ComponentPropertiesAsList Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.KitLineProductPropertyDictionary.ComponentPropertiesAsList
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.kitlineproductpropertydictionary.componentpropertiesaslist(v=AX.60)
ms:contentKeyID: 62207108
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.KitLineProductPropertyDictionary.ComponentPropertiesAsList
dev_langs:
- CSharp
- C++
- VB
---

# ComponentPropertiesAsList Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a list of the kit line product properties, qualified by the productId.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property ComponentPropertiesAsList As ICollection(Of KitLineProductProperty)
    Get
'Usage
Dim instance As KitLineProductPropertyDictionary
Dim value As ICollection(Of KitLineProductProperty)

value = instance.ComponentPropertiesAsList
```

``` csharp
public ICollection<KitLineProductProperty> ComponentPropertiesAsList { get; }
```

``` c++
public:
property ICollection<KitLineProductProperty^>^ ComponentPropertiesAsList {
    ICollection<KitLineProductProperty^>^ get ();
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[KitLineProductProperty](kitlineproductproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ICollection\<T\>](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\)).  

## See Also

#### Reference

[KitLineProductPropertyDictionary Class](kitlineproductpropertydictionary-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


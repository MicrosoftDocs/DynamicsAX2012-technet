---
title: KitVariantToComponentDictionary.KitVariantToComponentDictionaryAsList Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: KitVariantToComponentDictionaryAsList Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.KitVariantToComponentDictionary.KitVariantToComponentDictionaryAsList
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.kitvarianttocomponentdictionary.kitvarianttocomponentdictionaryaslist(v=AX.60)
ms:contentKeyID: 62212330
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.KitVariantToComponentDictionary.KitVariantToComponentDictionaryAsList
dev_langs:
- CSharp
- C++
- VB
---

# KitVariantToComponentDictionaryAsList Property

Gets a flat listed collection of kit variant to component associations ([KitVariantContent](kitvariantcontent-class-microsoft-dynamics-commerce-runtime-datamodel.md) objects).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property KitVariantToComponentDictionaryAsList As ICollection(Of KitVariantContent)
    Get
'Usage
Dim instance As KitVariantToComponentDictionary
Dim value As ICollection(Of KitVariantContent)

value = instance.KitVariantToComponentDictionaryAsList
```

``` csharp
public ICollection<KitVariantContent> KitVariantToComponentDictionaryAsList { get; }
```

``` c++
public:
property ICollection<KitVariantContent^>^ KitVariantToComponentDictionaryAsList {
    ICollection<KitVariantContent^>^ get ();
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[KitVariantContent](kitvariantcontent-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ICollection\<T\>](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\)).  

## See Also

#### Reference

[KitVariantToComponentDictionary Class](kitvarianttocomponentdictionary-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


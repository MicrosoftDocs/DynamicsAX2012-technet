---
title: KitVariantContent.KitComponentKeyList Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: KitComponentKeyList Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.KitVariantContent.KitComponentKeyList
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.kitvariantcontent.kitcomponentkeylist(v=AX.60)
ms:contentKeyID: 62208181
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.KitVariantContent.KitComponentKeyList
dev_langs:
- CSharp
- C++
- VB
---

# KitComponentKeyList Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a collection of [KitComponentKey](kitcomponentkey-class-microsoft-dynamics-commerce-runtime-datamodel.md) objects that represent the component's productId and its position in the KitLineDefinition.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property KitComponentKeyList As ICollection(Of KitComponentKey)
    Get
    Friend Set
'Usage
Dim instance As KitVariantContent
Dim value As ICollection(Of KitComponentKey)

value = instance.KitComponentKeyList
```

``` csharp
[DataMemberAttribute]
public ICollection<KitComponentKey> KitComponentKeyList { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<KitComponentKey^>^ KitComponentKeyList {
    ICollection<KitComponentKey^>^ get ();
    internal: void set (ICollection<KitComponentKey^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[KitComponentKey](kitcomponentkey-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ICollection\<T\>](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\)).  

## See Also

#### Reference

[KitVariantContent Class](kitvariantcontent-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


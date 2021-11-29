---
title: KitVariantContent Constructor (Int64, ICollection(KitComponentKey)) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: KitVariantContent Constructor (Int64, ICollection(KitComponentKey))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.KitVariantContent.#ctor(System.Int64,System.Collections.Generic.ICollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.KitComponentKey})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.kitvariantcontent.kitvariantcontent(v=AX.60)
ms:contentKeyID: 62206614
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# KitVariantContent Constructor (Int64, ICollection(KitComponentKey))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [KitVariantContent](kitvariantcontent-class-microsoft-dynamics-commerce-runtime-datamodel.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    kitVariantId As Long, _
    kitComponentKeyList As ICollection(Of KitComponentKey) _
)
'Usage
Dim kitVariantId As Long
Dim kitComponentKeyList As ICollection(Of KitComponentKey)

Dim instance As New KitVariantContent(kitVariantId, _
    kitComponentKeyList)
```

``` csharp
public KitVariantContent(
    long kitVariantId,
    ICollection<KitComponentKey> kitComponentKeyList
)
```

``` c++
public:
KitVariantContent(
    long long kitVariantId, 
    ICollection<KitComponentKey^>^ kitComponentKeyList
)
```

#### Parameters

  - kitVariantId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - kitComponentKeyList  
    Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[KitComponentKey](kitcomponentkey-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[KitVariantContent Class](kitvariantcontent-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[KitVariantContent Overload](kitvariantcontent-constructor-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


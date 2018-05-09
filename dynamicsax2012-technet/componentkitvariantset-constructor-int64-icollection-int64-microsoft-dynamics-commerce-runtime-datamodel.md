---
title: ComponentKitVariantSet Constructor (Int64, ICollection(Int64)) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ComponentKitVariantSet Constructor (Int64, ICollection(Int64))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ComponentKitVariantSet.#ctor(System.Int64,System.Collections.Generic.ICollection{System.Int64})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.componentkitvariantset.componentkitvariantset(v=AX.60)
ms:contentKeyID: 62211158
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ComponentKitVariantSet Constructor (Int64, ICollection(Int64))

Initializes a new instance of the [ComponentKitVariantSet](componentkitvariantset-class-microsoft-dynamics-commerce-runtime-datamodel.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    kitLineProductId As Long, _
    kitVariantIdList As ICollection(Of Long) _
)
'Usage
Dim kitLineProductId As Long
Dim kitVariantIdList As ICollection(Of Long)

Dim instance As New ComponentKitVariantSet(kitLineProductId, _
    kitVariantIdList)
```

``` csharp
public ComponentKitVariantSet(
    long kitLineProductId,
    ICollection<long> kitVariantIdList
)
```

``` c++
public:
ComponentKitVariantSet(
    long long kitLineProductId, 
    ICollection<long long>^ kitVariantIdList
)
```

#### Parameters

  - kitLineProductId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - kitVariantIdList  
    Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/en-us/library/92t2ye13\(v=ax.60\))\<[Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))\>  

## See Also

#### Reference

[ComponentKitVariantSet Class](componentkitvariantset-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[ComponentKitVariantSet Overload](componentkitvariantset-constructor-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


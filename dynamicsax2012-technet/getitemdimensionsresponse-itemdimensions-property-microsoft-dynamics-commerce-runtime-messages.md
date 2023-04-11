---
title: GetItemDimensionsResponse.ItemDimensions Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ItemDimensions Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetItemDimensionsResponse.ItemDimensions
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getitemdimensionsresponse.itemdimensions(v=AX.60)
ms:contentKeyID: 62209361
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetItemDimensionsResponse.ItemDimensions
dev_langs:
- CSharp
- C++
- VB
---

# ItemDimensions Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of item dimensions.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ItemDimensions As ReadOnlyCollection(Of ItemDimensions)
    Get
    Private Set
'Usage
Dim instance As GetItemDimensionsResponse
Dim value As ReadOnlyCollection(Of ItemDimensions)

value = instance.ItemDimensions
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<ItemDimensions> ItemDimensions { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<ItemDimensions^>^ ItemDimensions {
    ReadOnlyCollection<ItemDimensions^>^ get ();
    private: void set (ReadOnlyCollection<ItemDimensions^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ItemDimensions](itemdimensions-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetItemDimensionsResponse Class](getitemdimensionsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


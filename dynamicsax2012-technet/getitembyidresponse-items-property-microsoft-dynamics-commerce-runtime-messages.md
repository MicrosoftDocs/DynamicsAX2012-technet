---
title: GetItemByIdResponse.Items Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Items Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetItemByIdResponse.Items
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getitembyidresponse.items(v=AX.60)
ms:contentKeyID: 49837026
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetItemByIdResponse.Items
dev_langs:
- CSharp
- C++
- VB
---

# Items Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of items.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Items As ReadOnlyCollection(Of Item)
    Get
    Private Set
'Usage
Dim instance As GetItemByIdResponse
Dim value As ReadOnlyCollection(Of Item)

value = instance.Items
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<Item> Items { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<Item^>^ Items {
    ReadOnlyCollection<Item^>^ get ();
    private: void set (ReadOnlyCollection<Item^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Item](item-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetItemByIdResponse Class](getitembyidresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


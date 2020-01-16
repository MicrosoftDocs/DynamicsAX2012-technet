---
title: GetItemsDataResponse.Items Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: Items Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetItemsDataResponse.Items
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getitemsdataresponse.items(v=AX.60)
ms:contentKeyID: 65321292
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetItemsDataResponse.Items
dev_langs:
- CSharp
- C++
- VB
---

# Items Property

Gets the item collection.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property Items As ReadOnlyCollection(Of Item)
    Get
    Private Set
'Usage
Dim instance As GetItemsDataResponse
Dim value As ReadOnlyCollection(Of Item)

value = instance.Items
```

``` csharp
public ReadOnlyCollection<Item> Items { get; private set; }
```

``` c++
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

[GetItemsDataResponse Class](getitemsdataresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


---
title: ICachedPricingDataManager.PutItems Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutItems Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedPricingDataManager.PutItems(System.Collections.Generic.IEnumerable{System.String},System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.Item})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.icachedpricingdatamanager.putitems(v=AX.60)
ms:contentKeyID: 62208350
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedPricingDataManager.PutItems
dev_langs:
- CSharp
- C++
- VB
---

# PutItems Method

Stores the items using the specified item identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutItems ( _
    itemIds As IEnumerable(Of String), _
    result As ReadOnlyCollection(Of Item) _
)
'Usage
Dim instance As ICachedPricingDataManager
Dim itemIds As IEnumerable(Of String)
Dim result As ReadOnlyCollection(Of Item)

instance.PutItems(itemIds, result)
```

``` csharp
void PutItems(
    IEnumerable<string> itemIds,
    ReadOnlyCollection<Item> result
)
```

``` c++
void PutItems(
    IEnumerable<String^>^ itemIds, 
    ReadOnlyCollection<Item^>^ result
)
```

#### Parameters

  - itemIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - result  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[Item](item-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ICachedPricingDataManager Interface](icachedpricingdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


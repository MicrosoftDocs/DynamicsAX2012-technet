---
title: ItemAvailabilitiesQueryCriteria.ItemWarehouses Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ItemWarehouses Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailabilitiesQueryCriteria.ItemWarehouses
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.itemavailabilitiesquerycriteria.itemwarehouses(v=AX.60)
ms:contentKeyID: 65319668
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailabilitiesQueryCriteria.ItemWarehouses
dev_langs:
- CSharp
- C++
- VB
---

# ItemWarehouses Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the items and corresponding inventory warehouses.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ItemWarehouses As IEnumerable(Of ItemWarehouse)
    Get
    Private Set
'Usage
Dim instance As ItemAvailabilitiesQueryCriteria
Dim value As IEnumerable(Of ItemWarehouse)

value = instance.ItemWarehouses
```

``` csharp
[DataMemberAttribute]
public IEnumerable<ItemWarehouse> ItemWarehouses { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<ItemWarehouse^>^ ItemWarehouses {
    IEnumerable<ItemWarehouse^>^ get ();
    private: void set (IEnumerable<ItemWarehouse^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ItemWarehouse](itemwarehouse-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[ItemAvailabilitiesQueryCriteria Class](itemavailabilitiesquerycriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


---
title: ItemAvailabilitiesQueryCriteria.MaxWarehousesPerItem Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MaxWarehousesPerItem Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailabilitiesQueryCriteria.MaxWarehousesPerItem
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.itemavailabilitiesquerycriteria.maxwarehousesperitem(v=AX.60)
ms:contentKeyID: 65316650
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailabilitiesQueryCriteria.MaxWarehousesPerItem
dev_langs:
- CSharp
- C++
- VB
---

# MaxWarehousesPerItem Property

Gets the maximum number of warehouses per item.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property MaxWarehousesPerItem As Nullable(Of Integer)
    Get
    Private Set
'Usage
Dim instance As ItemAvailabilitiesQueryCriteria
Dim value As Nullable(Of Integer)

value = instance.MaxWarehousesPerItem
```

``` csharp
[DataMemberAttribute]
public Nullable<int> MaxWarehousesPerItem { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Nullable<int> MaxWarehousesPerItem {
    Nullable<int> get ();
    private: void set (Nullable<int> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\))\<[Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))\>  
The maximum number of warehouses per item.  

## See Also

#### Reference

[ItemAvailabilitiesQueryCriteria Class](itemavailabilitiesquerycriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


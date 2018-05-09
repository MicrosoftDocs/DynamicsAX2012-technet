---
title: ItemAvailabilitiesQueryCriteria.ItemQuantities Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ItemQuantities Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailabilitiesQueryCriteria.ItemQuantities
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.itemavailabilitiesquerycriteria.itemquantities(v=AX.60)
ms:contentKeyID: 65322484
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailabilitiesQueryCriteria.ItemQuantities
dev_langs:
- CSharp
- C++
- VB
---

# ItemQuantities Property

Gets the collection of item and quantities.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ItemQuantities As IEnumerable(Of ItemQuantity)
    Get
    Private Set
'Usage
Dim instance As ItemAvailabilitiesQueryCriteria
Dim value As IEnumerable(Of ItemQuantity)

value = instance.ItemQuantities
```

``` csharp
[DataMemberAttribute]
public IEnumerable<ItemQuantity> ItemQuantities { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<ItemQuantity^>^ ItemQuantities {
    IEnumerable<ItemQuantity^>^ get ();
    private: void set (IEnumerable<ItemQuantity^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[ItemQuantity](itemquantity-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[ItemAvailabilitiesQueryCriteria Class](itemavailabilitiesquerycriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


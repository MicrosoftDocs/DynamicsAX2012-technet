---
title: ShippingDataManager.GetWarehouseDetails Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetWarehouseDetails Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ShippingDataManager.GetWarehouseDetails(System.Collections.Generic.IEnumerable{System.String},Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.shippingdatamanager.getwarehousedetails(v=AX.60)
ms:contentKeyID: 49853718
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ShippingDataManager.GetWarehouseDetails
dev_langs:
- CSharp
- C++
- VB
---

# GetWarehouseDetails Method

Gets the warehouse details.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetWarehouseDetails ( _
    warehouseIds As IEnumerable(Of String), _
    columns As ColumnSet _
) As ReadOnlyCollection(Of WarehouseDetails)
'Usage
Dim instance As ShippingDataManager
Dim warehouseIds As IEnumerable(Of String)
Dim columns As ColumnSet
Dim returnValue As ReadOnlyCollection(Of WarehouseDetails)

returnValue = instance.GetWarehouseDetails(warehouseIds, _
    columns)
```

``` csharp
public ReadOnlyCollection<WarehouseDetails> GetWarehouseDetails(
    IEnumerable<string> warehouseIds,
    ColumnSet columns
)
```

``` c++
public:
ReadOnlyCollection<WarehouseDetails^>^ GetWarehouseDetails(
    IEnumerable<String^>^ warehouseIds, 
    ColumnSet^ columns
)
```

#### Parameters

  - warehouseIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[WarehouseDetails](warehousedetails-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The collection of warehouse identifiers along with their addresses.  

## See Also

#### Reference

[ShippingDataManager Class](shippingdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


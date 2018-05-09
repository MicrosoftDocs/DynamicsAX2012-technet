---
title: InventoryManager.GetWarehouseDetails Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetWarehouseDetails Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.GetWarehouseDetails(System.Collections.Generic.IEnumerable{System.String},Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.inventorymanager.getwarehousedetails(v=AX.60)
ms:contentKeyID: 62214322
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.GetWarehouseDetails
dev_langs:
- CSharp
- C++
- VB
---

# GetWarehouseDetails Method

Gets the warehouse details.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetWarehouseDetails ( _
    warehouseIds As IEnumerable(Of String), _
    columns As ColumnSet _
) As ReadOnlyCollection(Of WarehouseDetails)
'Usage
Dim instance As InventoryManager
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
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[WarehouseDetails](warehousedetails-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The collection of warehouse identifiers along with their addresses.  

## See Also

#### Reference

[InventoryManager Class](inventorymanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)


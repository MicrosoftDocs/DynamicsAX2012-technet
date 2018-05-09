---
title: InventoryManager.GetItemAvailableQuantities Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetItemAvailableQuantities Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.GetItemAvailableQuantities(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemUnit},System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.inventorymanager.getitemavailablequantities(v=AX.60)
ms:contentKeyID: 65318810
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.GetItemAvailableQuantities
dev_langs:
- CSharp
- C++
- VB
---

# GetItemAvailableQuantities Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetItemAvailableQuantities ( _
    settings As QueryResultSettings, _
    itemUnits As IEnumerable(Of ItemUnit), _
    customerAccountNumber As String _
) As ReadOnlyCollection(Of ItemAvailableQuantity)
'Usage
Dim instance As InventoryManager
Dim settings As QueryResultSettings
Dim itemUnits As IEnumerable(Of ItemUnit)
Dim customerAccountNumber As String
Dim returnValue As ReadOnlyCollection(Of ItemAvailableQuantity)

returnValue = instance.GetItemAvailableQuantities(settings, _
    itemUnits, customerAccountNumber)
```

``` csharp
public ReadOnlyCollection<ItemAvailableQuantity> GetItemAvailableQuantities(
    QueryResultSettings settings,
    IEnumerable<ItemUnit> itemUnits,
    string customerAccountNumber
)
```

``` c++
public:
ReadOnlyCollection<ItemAvailableQuantity^>^ GetItemAvailableQuantities(
    QueryResultSettings^ settings, 
    IEnumerable<ItemUnit^>^ itemUnits, 
    String^ customerAccountNumber
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - itemUnits  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[ItemUnit](itemunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - customerAccountNumber  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[ItemAvailableQuantity](itemavailablequantity-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[InventoryManager Class](inventorymanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)


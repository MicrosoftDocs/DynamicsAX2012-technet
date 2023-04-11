---
title: InventoryManager.GetAvailableInventory Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetAvailableInventory Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.GetAvailableInventory(System.String,System.String,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.inventorymanager.getavailableinventory(v=AX.60)
ms:contentKeyID: 65318393
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.GetAvailableInventory
dev_langs:
- CSharp
- C++
- VB
---

# GetAvailableInventory Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetAvailableInventory ( _
    itemId As String, _
    variantId As String, _
    barcode As String, _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of OrgUnitAvailability)
'Usage
Dim instance As InventoryManager
Dim itemId As String
Dim variantId As String
Dim barcode As String
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of OrgUnitAvailability)

returnValue = instance.GetAvailableInventory(itemId, _
    variantId, barcode, settings)
```

``` csharp
public ReadOnlyCollection<OrgUnitAvailability> GetAvailableInventory(
    string itemId,
    string variantId,
    string barcode,
    QueryResultSettings settings
)
```

``` c++
public:
ReadOnlyCollection<OrgUnitAvailability^>^ GetAvailableInventory(
    String^ itemId, 
    String^ variantId, 
    String^ barcode, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - itemId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - variantId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - barcode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[OrgUnitAvailability](orgunitavailability-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[InventoryManager Class](inventorymanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)


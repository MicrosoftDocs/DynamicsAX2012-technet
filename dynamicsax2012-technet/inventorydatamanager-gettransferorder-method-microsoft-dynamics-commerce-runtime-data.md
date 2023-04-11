---
title: InventoryDataManager.GetTransferOrder Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetTransferOrder Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.InventoryDataManager.GetTransferOrder(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.inventorydatamanager.gettransferorder(v=AX.60)
ms:contentKeyID: 65316863
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.InventoryDataManager.GetTransferOrder
dev_langs:
- CSharp
- C++
- VB
---

# GetTransferOrder Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetTransferOrder ( _
    orderId As String, _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of TransferOrderLine)
'Usage
Dim instance As InventoryDataManager
Dim orderId As String
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of TransferOrderLine)

returnValue = instance.GetTransferOrder(orderId, _
    settings)
```

``` csharp
public ReadOnlyCollection<TransferOrderLine> GetTransferOrder(
    string orderId,
    QueryResultSettings settings
)
```

``` c++
public:
ReadOnlyCollection<TransferOrderLine^>^ GetTransferOrder(
    String^ orderId, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - orderId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[TransferOrderLine](transferorderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[InventoryDataManager Class](inventorydatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


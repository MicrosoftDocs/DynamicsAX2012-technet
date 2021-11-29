---
title: InventoryDataManager.DeletePickingListLines Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: DeletePickingListLines Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.InventoryDataManager.DeletePickingListLines(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.inventorydatamanager.deletepickinglistlines(v=AX.60)
ms:contentKeyID: 62213405
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.InventoryDataManager.DeletePickingListLines
dev_langs:
- CSharp
- C++
- VB
---

# DeletePickingListLines Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Deletes picking list lines for a order saved in the database.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function DeletePickingListLines ( _
    orderId As String _
) As Integer
'Usage
Dim instance As InventoryDataManager
Dim orderId As String
Dim returnValue As Integer

returnValue = instance.DeletePickingListLines(orderId)
```

``` csharp
public int DeletePickingListLines(
    string orderId
)
```

``` c++
public:
int DeletePickingListLines(
    String^ orderId
)
```

#### Parameters

  - orderId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Whether the operation is successful or not..  

## See Also

#### Reference

[InventoryDataManager Class](inventorydatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


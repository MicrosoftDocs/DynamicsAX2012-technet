---
title: InventoryDataManager.DeletePurchaseOrderLines Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: DeletePurchaseOrderLines Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.InventoryDataManager.DeletePurchaseOrderLines(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.inventorydatamanager.deletepurchaseorderlines(v=AX.60)
ms:contentKeyID: 62209803
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.InventoryDataManager.DeletePurchaseOrderLines
dev_langs:
- CSharp
- C++
- VB
---

# DeletePurchaseOrderLines Method

Gets transfer order lines for a order saved in the database.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function DeletePurchaseOrderLines ( _
    orderId As String _
) As Integer
'Usage
Dim instance As InventoryDataManager
Dim orderId As String
Dim returnValue As Integer

returnValue = instance.DeletePurchaseOrderLines(orderId)
```

``` csharp
public int DeletePurchaseOrderLines(
    string orderId
)
```

``` c++
public:
int DeletePurchaseOrderLines(
    String^ orderId
)
```

#### Parameters

  - orderId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
The collection of transfer order lines.  

## See Also

#### Reference

[InventoryDataManager Class](inventorydatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


---
title: IItemSystemV1.GetBarcodesForItem Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: GetBarcodesForItem Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IItemSystemV1.GetBarcodesForItem(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.iitemsystemv1.getbarcodesforitem(v=AX.60)
ms:contentKeyID: 47128647
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IItemSystemV1.GetBarcodesForItem
dev_langs:
- CSharp
- C++
- VB
---

# GetBarcodesForItem Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the barcodes for an item.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function GetBarcodesForItem ( _
    selectedItemId As String _
) As DataTable
'Usage
Dim instance As IItemSystemV1
Dim selectedItemId As String
Dim returnValue As DataTable

returnValue = instance.GetBarcodesForItem(selectedItemId)
```

``` csharp
DataTable GetBarcodesForItem(
    string selectedItemId
)
```

``` c++
DataTable^ GetBarcodesForItem(
    String^ selectedItemId
)
```

#### Parameters

  - selectedItemId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Data.DataTable](https://technet.microsoft.com/library/9186hy08\(v=ax.60\))  
The list of barcodes for the given item.  

## See Also

#### Reference

[IItemSystemV1 Interface](iitemsystemv1-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)


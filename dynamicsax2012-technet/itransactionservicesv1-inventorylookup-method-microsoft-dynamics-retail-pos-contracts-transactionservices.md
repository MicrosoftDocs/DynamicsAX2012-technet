---
title: ITransactionServicesV1.InventoryLookup Method  (Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices)
TOCTitle: InventoryLookup Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.InventoryLookup(System.Boolean@,System.String@,System.Data.DataTable@,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.transactionservices.itransactionservicesv1.inventorylookup(v=AX.60)
ms:contentKeyID: 47128798
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.InventoryLookup
dev_langs:
- CSharp
- C++
- VB
---

# InventoryLookup Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub InventoryLookup ( _
    ByRef retValue As Boolean, _
    ByRef comment As String, _
    ByRef inventoryTable As DataTable, _
    itemId As String, _
    variantId As String _
)
'Usage
Dim instance As ITransactionServicesV1
Dim retValue As Boolean
Dim comment As String
Dim inventoryTable As DataTable
Dim itemId As String
Dim variantId As String

instance.InventoryLookup(retValue, comment, _
    inventoryTable, itemId, variantId)
```

``` csharp
void InventoryLookup(
    ref bool retValue,
    ref string comment,
    ref DataTable inventoryTable,
    string itemId,
    string variantId
)
```

``` c++
void InventoryLookup(
    bool% retValue, 
    String^% comment, 
    DataTable^% inventoryTable, 
    String^ itemId, 
    String^ variantId
)
```

#### Parameters

  - retValue  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - comment  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - inventoryTable  
    Type: [System.Data.DataTable](https://technet.microsoft.com/library/9186hy08\(v=ax.60\))  

<!-- end list -->

  - itemId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - variantId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ITransactionServicesV1 Interface](itransactionservicesv1-interface-microsoft-dynamics-retail-pos-contracts-transactionservices.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices Namespace](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)


---
title: ISuspendRetrieveSystemV1.RetrieveTransactionList Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: RetrieveTransactionList Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ISuspendRetrieveSystemV1.RetrieveTransactionList(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.isuspendretrievesystemv1.retrievetransactionlist(v=AX.60)
ms:contentKeyID: 62205179
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ISuspendRetrieveSystemV1.RetrieveTransactionList
dev_langs:
- CSharp
- C++
- VB
---

# RetrieveTransactionList Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Retrieves the list of transactions from a store.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function RetrieveTransactionList ( _
    storeId As String _
) As DataTable
'Usage
Dim instance As ISuspendRetrieveSystemV1
Dim storeId As String
Dim returnValue As DataTable

returnValue = instance.RetrieveTransactionList(storeId)
```

``` csharp
DataTable RetrieveTransactionList(
    string storeId
)
```

``` c++
DataTable^ RetrieveTransactionList(
    String^ storeId
)
```

#### Parameters

  - storeId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Data.DataTable](https://technet.microsoft.com/library/9186hy08\(v=ax.60\))  
The list of transactions on the given store.  

## See Also

#### Reference

[ISuspendRetrieveSystemV1 Interface](isuspendretrievesystemv1-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)


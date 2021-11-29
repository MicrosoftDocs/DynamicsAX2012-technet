---
title: ITransactionSystemV2.GetRetailTransaction Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: GetRetailTransaction Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ITransactionSystemV2.GetRetailTransaction(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,System.String,System.String,System.String,System.Data.DataTable,System.Data.DataTable,System.Data.DataTable,System.Data.DataTable)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.itransactionsystemv2.getretailtransaction(v=AX.60)
ms:contentKeyID: 62202354
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ITransactionSystemV2.GetRetailTransaction
dev_langs:
- CSharp
- C++
- VB
---

# GetRetailTransaction Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function GetRetailTransaction ( _
    transaction As IPosTransaction, _
    storeId As String, _
    terminalId As String, _
    receiptId As String, _
    transHeader As DataTable, _
    transItems As DataTable, _
    transLoyalty As DataTable, _
    transDiscounts As DataTable _
) As IRetailTransaction
'Usage
Dim instance As ITransactionSystemV2
Dim transaction As IPosTransaction
Dim storeId As String
Dim terminalId As String
Dim receiptId As String
Dim transHeader As DataTable
Dim transItems As DataTable
Dim transLoyalty As DataTable
Dim transDiscounts As DataTable
Dim returnValue As IRetailTransaction

returnValue = instance.GetRetailTransaction(transaction, _
    storeId, terminalId, receiptId, transHeader, _
    transItems, transLoyalty, transDiscounts)
```

``` csharp
IRetailTransaction GetRetailTransaction(
    IPosTransaction transaction,
    string storeId,
    string terminalId,
    string receiptId,
    DataTable transHeader,
    DataTable transItems,
    DataTable transLoyalty,
    DataTable transDiscounts
)
```

``` c++
IRetailTransaction^ GetRetailTransaction(
    IPosTransaction^ transaction, 
    String^ storeId, 
    String^ terminalId, 
    String^ receiptId, 
    DataTable^ transHeader, 
    DataTable^ transItems, 
    DataTable^ transLoyalty, 
    DataTable^ transDiscounts
)
```

#### Parameters

  - transaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - storeId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - receiptId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - transHeader  
    Type: [System.Data.DataTable](https://technet.microsoft.com/library/9186hy08\(v=ax.60\))  

<!-- end list -->

  - transItems  
    Type: [System.Data.DataTable](https://technet.microsoft.com/library/9186hy08\(v=ax.60\))  

<!-- end list -->

  - transLoyalty  
    Type: [System.Data.DataTable](https://technet.microsoft.com/library/9186hy08\(v=ax.60\))  

<!-- end list -->

  - transDiscounts  
    Type: [System.Data.DataTable](https://technet.microsoft.com/library/9186hy08\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
Returns [IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md).  

## See Also

#### Reference

[ITransactionSystemV2 Interface](itransactionsystemv2-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)


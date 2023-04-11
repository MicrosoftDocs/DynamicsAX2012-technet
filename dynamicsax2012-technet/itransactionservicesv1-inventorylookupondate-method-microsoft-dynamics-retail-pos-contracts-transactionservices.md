---
title: ITransactionServicesV1.InventoryLookupOnDate Method  (Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices)
TOCTitle: InventoryLookupOnDate Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.InventoryLookupOnDate(System.Boolean@,System.String@,System.Data.DataTable@,System.String,System.String,System.DateTime)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.transactionservices.itransactionservicesv1.inventorylookupondate(v=AX.60)
ms:contentKeyID: 49830743
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.InventoryLookupOnDate
dev_langs:
- CSharp
- C++
- VB
---

# InventoryLookupOnDate Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub InventoryLookupOnDate ( _
    ByRef retValue As Boolean, _
    ByRef comment As String, _
    ByRef inventoryTable As DataTable, _
    itemId As String, _
    variantId As String, _
    transDate As DateTime _
)
'Usage
Dim instance As ITransactionServicesV1
Dim retValue As Boolean
Dim comment As String
Dim inventoryTable As DataTable
Dim itemId As String
Dim variantId As String
Dim transDate As DateTime

instance.InventoryLookupOnDate(retValue, _
    comment, inventoryTable, itemId, _
    variantId, transDate)
```

``` csharp
void InventoryLookupOnDate(
    ref bool retValue,
    ref string comment,
    ref DataTable inventoryTable,
    string itemId,
    string variantId,
    DateTime transDate
)
```

``` c++
void InventoryLookupOnDate(
    bool% retValue, 
    String^% comment, 
    DataTable^% inventoryTable, 
    String^ itemId, 
    String^ variantId, 
    DateTime transDate
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

<!-- end list -->

  - transDate  
    Type: [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))  

## See Also

#### Reference

[ITransactionServicesV1 Interface](itransactionservicesv1-interface-microsoft-dynamics-retail-pos-contracts-transactionservices.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices Namespace](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)


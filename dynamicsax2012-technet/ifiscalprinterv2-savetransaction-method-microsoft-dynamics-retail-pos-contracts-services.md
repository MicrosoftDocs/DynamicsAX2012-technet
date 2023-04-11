---
title: IFiscalPrinterV2.SaveTransaction Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: SaveTransaction Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV2.SaveTransaction(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,System.Data.SqlClient.SqlTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ifiscalprinterv2.savetransaction(v=AX.60)
ms:contentKeyID: 62204718
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV2.SaveTransaction
dev_langs:
- CSharp
- C++
- VB
---

# SaveTransaction Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Triggered during save of a transaction to database.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub SaveTransaction ( _
    posTransaction As IPosTransaction, _
    sqlTransaction As SqlTransaction _
)
'Usage
Dim instance As IFiscalPrinterV2
Dim posTransaction As IPosTransaction
Dim sqlTransaction As SqlTransaction

instance.SaveTransaction(posTransaction, _
    sqlTransaction)
```

``` csharp
void SaveTransaction(
    IPosTransaction posTransaction,
    SqlTransaction sqlTransaction
)
```

``` c++
void SaveTransaction(
    IPosTransaction^ posTransaction, 
    SqlTransaction^ sqlTransaction
)
```

#### Parameters

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - sqlTransaction  
    Type: [System.Data.SqlClient.SqlTransaction](https://technet.microsoft.com/library/4b1h6b1d\(v=ax.60\))  

## See Also

#### Reference

[IFiscalPrinterV2 Interface](ifiscalprinterv2-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)


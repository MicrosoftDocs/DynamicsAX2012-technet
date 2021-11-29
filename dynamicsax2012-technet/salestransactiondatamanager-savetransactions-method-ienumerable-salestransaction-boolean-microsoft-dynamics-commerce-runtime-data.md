---
title: SalesTransactionDataManager.SaveTransactions Method (IEnumerable(SalesTransaction), Boolean) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: SaveTransactions Method (IEnumerable(SalesTransaction), Boolean)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.SalesTransactionDataManager.SaveTransactions(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction},System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.salestransactiondatamanager.savetransactions(v=AX.60)
ms:contentKeyID: 65321821
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SaveTransactions Method (IEnumerable(SalesTransaction), Boolean)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Sub SaveTransactions ( _
    salesTransactions As IEnumerable(Of SalesTransaction), _
    ignoreRowVersionCheck As Boolean _
)
'Usage
Dim instance As SalesTransactionDataManager
Dim salesTransactions As IEnumerable(Of SalesTransaction)
Dim ignoreRowVersionCheck As Boolean

instance.SaveTransactions(salesTransactions, _
    ignoreRowVersionCheck)
```

``` csharp
public void SaveTransactions(
    IEnumerable<SalesTransaction> salesTransactions,
    bool ignoreRowVersionCheck
)
```

``` c++
public:
void SaveTransactions(
    IEnumerable<SalesTransaction^>^ salesTransactions, 
    bool ignoreRowVersionCheck
)
```

#### Parameters

  - salesTransactions  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - ignoreRowVersionCheck  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[SalesTransactionDataManager Class](salestransactiondatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[SaveTransactions Overload](salestransactiondatamanager-savetransactions-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


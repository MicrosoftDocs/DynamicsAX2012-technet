---
title: SalesOrderDataManager.GetStoreId Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetStoreId Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.SalesOrderDataManager.GetStoreId(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.salesorderdatamanager.getstoreid(v=AX.60)
ms:contentKeyID: 62213903
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.SalesOrderDataManager.GetStoreId
dev_langs:
- CSharp
- C++
- VB
---

# GetStoreId Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the store associated with the sales transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Protected Function GetStoreId ( _
    transaction As SalesTransaction _
) As String
'Usage
Dim transaction As SalesTransaction
Dim returnValue As String

returnValue = Me.GetStoreId(transaction)
```

``` csharp
protected string GetStoreId(
    SalesTransaction transaction
)
```

``` c++
protected:
String^ GetStoreId(
    SalesTransaction^ transaction
)
```

#### Parameters

  - transaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The store identifier.  

## See Also

#### Reference

[SalesOrderDataManager Class](salesorderdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


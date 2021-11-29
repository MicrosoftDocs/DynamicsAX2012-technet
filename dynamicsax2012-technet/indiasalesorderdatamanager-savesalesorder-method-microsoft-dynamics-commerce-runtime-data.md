---
title: IndiaSalesOrderDataManager.SaveSalesOrder Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: SaveSalesOrder Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IndiaSalesOrderDataManager.SaveSalesOrder(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.indiasalesorderdatamanager.savesalesorder(v=AX.60)
ms:contentKeyID: 62207900
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IndiaSalesOrderDataManager.SaveSalesOrder
dev_langs:
- CSharp
- C++
- VB
---

# SaveSalesOrder Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Saves the sales order.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Overrides Sub SaveSalesOrder ( _
    transaction As SalesTransaction _
)
'Usage
Dim instance As IndiaSalesOrderDataManager
Dim transaction As SalesTransaction

instance.SaveSalesOrder(transaction)
```

``` csharp
public override void SaveSalesOrder(
    SalesTransaction transaction
)
```

``` c++
public:
virtual void SaveSalesOrder(
    SalesTransaction^ transaction
) override
```

#### Parameters

  - transaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[IndiaSalesOrderDataManager Class](indiasalesorderdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


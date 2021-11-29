---
title: SalesOrderDataManager.FillSalesOrderMembers Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: FillSalesOrderMembers Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.SalesOrderDataManager.FillSalesOrderMembers(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrder},System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.salesorderdatamanager.fillsalesordermembers(v=AX.60)
ms:contentKeyID: 62207737
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.SalesOrderDataManager.FillSalesOrderMembers
dev_langs:
- CSharp
- C++
- VB
---

# FillSalesOrderMembers Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Process sales order filling details.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Overridable Sub FillSalesOrderMembers ( _
    salesOrders As IEnumerable(Of SalesOrder), _
    includeDetails As Boolean _
)
'Usage
Dim instance As SalesOrderDataManager
Dim salesOrders As IEnumerable(Of SalesOrder)
Dim includeDetails As Boolean

instance.FillSalesOrderMembers(salesOrders, _
    includeDetails)
```

``` csharp
public virtual void FillSalesOrderMembers(
    IEnumerable<SalesOrder> salesOrders,
    bool includeDetails
)
```

``` c++
public:
virtual void FillSalesOrderMembers(
    IEnumerable<SalesOrder^>^ salesOrders, 
    bool includeDetails
)
```

#### Parameters

  - salesOrders  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[SalesOrder](salesorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - includeDetails  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[SalesOrderDataManager Class](salesorderdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


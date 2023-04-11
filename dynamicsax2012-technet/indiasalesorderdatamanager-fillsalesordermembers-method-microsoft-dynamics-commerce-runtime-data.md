---
title: IndiaSalesOrderDataManager.FillSalesOrderMembers Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: FillSalesOrderMembers Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IndiaSalesOrderDataManager.FillSalesOrderMembers(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrder},System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.indiasalesorderdatamanager.fillsalesordermembers(v=AX.60)
ms:contentKeyID: 65321651
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IndiaSalesOrderDataManager.FillSalesOrderMembers
dev_langs:
- CSharp
- C++
- VB
---

# FillSalesOrderMembers Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

This member overrides [SalesOrderDataManager.FillSalesOrderMembers(IEnumerable\<SalesOrder\>, Boolean)](salesorderdatamanager-fillsalesordermembers-method-microsoft-dynamics-commerce-runtime-data.md).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Overrides Sub FillSalesOrderMembers ( _
    salesOrders As IEnumerable(Of SalesOrder), _
    includeDetails As Boolean _
)
'Usage
Dim instance As IndiaSalesOrderDataManager
Dim salesOrders As IEnumerable(Of SalesOrder)
Dim includeDetails As Boolean

instance.FillSalesOrderMembers(salesOrders, _
    includeDetails)
```

``` csharp
public override void FillSalesOrderMembers(
    IEnumerable<SalesOrder> salesOrders,
    bool includeDetails
)
```

``` c++
public:
virtual void FillSalesOrderMembers(
    IEnumerable<SalesOrder^>^ salesOrders, 
    bool includeDetails
) override
```

#### Parameters

  - salesOrders  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[SalesOrder](salesorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - includeDetails  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[IndiaSalesOrderDataManager Class](indiasalesorderdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


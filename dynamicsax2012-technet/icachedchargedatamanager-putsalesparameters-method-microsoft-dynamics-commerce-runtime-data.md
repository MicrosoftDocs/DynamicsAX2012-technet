---
title: ICachedChargeDataManager.PutSalesParameters Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutSalesParameters Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedChargeDataManager.PutSalesParameters(Microsoft.Dynamics.Commerce.Runtime.ColumnSet,Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesParameters)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.icachedchargedatamanager.putsalesparameters(v=AX.60)
ms:contentKeyID: 65319046
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedChargeDataManager.PutSalesParameters
dev_langs:
- CSharp
- C++
- VB
---

# PutSalesParameters Method

Caches the sales parameters.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutSalesParameters ( _
    columnSet As ColumnSet, _
    result As SalesParameters _
)
'Usage
Dim instance As ICachedChargeDataManager
Dim columnSet As ColumnSet
Dim result As SalesParameters

instance.PutSalesParameters(columnSet, _
    result)
```

``` csharp
void PutSalesParameters(
    ColumnSet columnSet,
    SalesParameters result
)
```

``` c++
void PutSalesParameters(
    ColumnSet^ columnSet, 
    SalesParameters^ result
)
```

#### Parameters

  - columnSet  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - result  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesParameters](salesparameters-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ICachedChargeDataManager Interface](icachedchargedatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


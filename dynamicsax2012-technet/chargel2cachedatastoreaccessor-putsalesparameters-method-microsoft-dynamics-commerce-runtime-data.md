---
title: ChargeL2CacheDataStoreAccessor.PutSalesParameters Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutSalesParameters Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ChargeL2CacheDataStoreAccessor.PutSalesParameters(Microsoft.Dynamics.Commerce.Runtime.ColumnSet,Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesParameters)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.chargel2cachedatastoreaccessor.putsalesparameters(v=AX.60)
ms:contentKeyID: 65316894
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ChargeL2CacheDataStoreAccessor.PutSalesParameters
dev_langs:
- CSharp
- C++
- VB
---

# PutSalesParameters Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Caches the sales parameters.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Sub PutSalesParameters ( _
    columnSet As ColumnSet, _
    result As SalesParameters _
)
'Usage
Dim instance As ChargeL2CacheDataStoreAccessor
Dim columnSet As ColumnSet
Dim result As SalesParameters

instance.PutSalesParameters(columnSet, _
    result)
```

``` csharp
public void PutSalesParameters(
    ColumnSet columnSet,
    SalesParameters result
)
```

``` c++
public:
virtual void PutSalesParameters(
    ColumnSet^ columnSet, 
    SalesParameters^ result
) sealed
```

#### Parameters

  - columnSet  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - result  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesParameters](salesparameters-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Implements

[ICachedChargeDataManager.PutSalesParameters(ColumnSet, SalesParameters)](icachedchargedatamanager-putsalesparameters-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[ChargeL2CacheDataStoreAccessor Class](chargel2cachedatastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


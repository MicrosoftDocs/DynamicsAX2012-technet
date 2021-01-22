---
title: ChargeL2CacheDataStoreAccessor.GetSalesParameters Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetSalesParameters Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ChargeL2CacheDataStoreAccessor.GetSalesParameters(Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.chargel2cachedatastoreaccessor.getsalesparameters(v=AX.60)
ms:contentKeyID: 65320418
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ChargeL2CacheDataStoreAccessor.GetSalesParameters
dev_langs:
- CSharp
- C++
- VB
---

# GetSalesParameters Method

Retrieves the single sales parameters record.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetSalesParameters ( _
    columnSet As ColumnSet _
) As SalesParameters
'Usage
Dim instance As ChargeL2CacheDataStoreAccessor
Dim columnSet As ColumnSet
Dim returnValue As SalesParameters

returnValue = instance.GetSalesParameters(columnSet)
```

``` csharp
public SalesParameters GetSalesParameters(
    ColumnSet columnSet
)
```

``` c++
public:
virtual SalesParameters^ GetSalesParameters(
    ColumnSet^ columnSet
) sealed
```

#### Parameters

  - columnSet  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesParameters](salesparameters-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The sales parameters.  

#### Implements

[ICachedChargeDataManager.GetSalesParameters(ColumnSet)](icachedchargedatamanager-getsalesparameters-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[ChargeL2CacheDataStoreAccessor Class](chargel2cachedatastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


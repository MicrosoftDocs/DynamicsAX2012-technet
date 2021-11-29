---
title: StoreOperationsManager.GetNonSaleTenderOperations Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetNonSaleTenderOperations Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.StoreOperationsManager.GetNonSaleTenderOperations(Microsoft.Dynamics.Commerce.Runtime.DataModel.NonSalesTenderType,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.storeoperationsmanager.getnonsaletenderoperations(v=AX.60)
ms:contentKeyID: 65317051
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.StoreOperationsManager.GetNonSaleTenderOperations
dev_langs:
- CSharp
- C++
- VB
---

# GetNonSaleTenderOperations Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetNonSaleTenderOperations ( _
    nonSalesTenderType As NonSalesTenderType, _
    shiftId As String, _
    queryResultSettings As QueryResultSettings _
) As PagedResult(Of NonSalesTransaction)
'Usage
Dim instance As StoreOperationsManager
Dim nonSalesTenderType As NonSalesTenderType
Dim shiftId As String
Dim queryResultSettings As QueryResultSettings
Dim returnValue As PagedResult(Of NonSalesTransaction)

returnValue = instance.GetNonSaleTenderOperations(nonSalesTenderType, _
    shiftId, queryResultSettings)
```

``` csharp
public PagedResult<NonSalesTransaction> GetNonSaleTenderOperations(
    NonSalesTenderType nonSalesTenderType,
    string shiftId,
    QueryResultSettings queryResultSettings
)
```

``` c++
public:
PagedResult<NonSalesTransaction^>^ GetNonSaleTenderOperations(
    NonSalesTenderType nonSalesTenderType, 
    String^ shiftId, 
    QueryResultSettings^ queryResultSettings
)
```

#### Parameters

  - nonSalesTenderType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.NonSalesTenderType](nonsalestendertype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - shiftId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - queryResultSettings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[NonSalesTransaction](nonsalestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[StoreOperationsManager Class](storeoperationsmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)


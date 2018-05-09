---
title: DataCacheAccessor.CalculateQueryCriteriaHash Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: CalculateQueryCriteriaHash Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DataCacheAccessor.CalculateQueryCriteriaHash(Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.datacacheaccessor.calculatequerycriteriahash(v=AX.60)
ms:contentKeyID: 65322171
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DataCacheAccessor.CalculateQueryCriteriaHash
dev_langs:
- CSharp
- C++
- VB
---

# CalculateQueryCriteriaHash Method

Calculates the signature of the criteria object.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Protected Shared Function CalculateQueryCriteriaHash ( _
    criteria As ProductSearchCriteria _
) As Integer
'Usage
Dim criteria As ProductSearchCriteria
Dim returnValue As Integer

returnValue = DataCacheAccessor.CalculateQueryCriteriaHash(criteria)
```

``` csharp
protected static int CalculateQueryCriteriaHash(
    ProductSearchCriteria criteria
)
```

``` c++
protected:
static int CalculateQueryCriteriaHash(
    ProductSearchCriteria^ criteria
)
```

#### Parameters

  - criteria  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria](productsearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
Cache key corresponding to this call.  

## See Also

#### Reference

[DataCacheAccessor Class](datacacheaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


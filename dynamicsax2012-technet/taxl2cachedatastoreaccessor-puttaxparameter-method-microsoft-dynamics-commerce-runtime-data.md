---
title: TaxL2CacheDataStoreAccessor.PutTaxParameter Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutTaxParameter Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.TaxL2CacheDataStoreAccessor.PutTaxParameter(Microsoft.Dynamics.Commerce.Runtime.ColumnSet,Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxParameters)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.taxl2cachedatastoreaccessor.puttaxparameter(v=AX.60)
ms:contentKeyID: 62204922
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.TaxL2CacheDataStoreAccessor.PutTaxParameter
dev_langs:
- CSharp
- C++
- VB
---

# PutTaxParameter Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Puts the tax parameters.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Sub PutTaxParameter ( _
    columns As ColumnSet, _
    result As TaxParameters _
)
'Usage
Dim instance As TaxL2CacheDataStoreAccessor
Dim columns As ColumnSet
Dim result As TaxParameters

instance.PutTaxParameter(columns, result)
```

``` csharp
public void PutTaxParameter(
    ColumnSet columns,
    TaxParameters result
)
```

``` c++
public:
void PutTaxParameter(
    ColumnSet^ columns, 
    TaxParameters^ result
)
```

#### Parameters

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - result  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxParameters](taxparameters-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[TaxL2CacheDataStoreAccessor Class](taxl2cachedatastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


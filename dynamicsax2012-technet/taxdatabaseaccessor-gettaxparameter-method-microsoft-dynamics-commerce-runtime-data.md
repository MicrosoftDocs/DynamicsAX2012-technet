---
title: TaxDatabaseAccessor.GetTaxParameter Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetTaxParameter Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.TaxDatabaseAccessor.GetTaxParameter(Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.taxdatabaseaccessor.gettaxparameter(v=AX.60)
ms:contentKeyID: 62204395
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.TaxDatabaseAccessor.GetTaxParameter
dev_langs:
- CSharp
- C++
- VB
---

# GetTaxParameter Method

Gets the tax parameter.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetTaxParameter ( _
    columns As ColumnSet _
) As TaxParameters
'Usage
Dim instance As TaxDatabaseAccessor
Dim columns As ColumnSet
Dim returnValue As TaxParameters

returnValue = instance.GetTaxParameter(columns)
```

``` csharp
public TaxParameters GetTaxParameter(
    ColumnSet columns
)
```

``` c++
public:
TaxParameters^ GetTaxParameter(
    ColumnSet^ columns
)
```

#### Parameters

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxParameters](taxparameters-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The taxparameter or NULL if not found.  

## See Also

#### Reference

[TaxDatabaseAccessor Class](taxdatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


---
title: TaxDatabaseAccessor.GetTaxCodeFormulaIndia Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetTaxCodeFormulaIndia Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.TaxDatabaseAccessor.GetTaxCodeFormulaIndia(System.String,System.String,Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.taxdatabaseaccessor.gettaxcodeformulaindia(v=AX.60)
ms:contentKeyID: 62212298
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.TaxDatabaseAccessor.GetTaxCodeFormulaIndia
dev_langs:
- CSharp
- C++
- VB
---

# GetTaxCodeFormulaIndia Method

Gets the tax code formula for India.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetTaxCodeFormulaIndia ( _
    itemTaxGroupId As String, _
    taxCode As String, _
    columns As ColumnSet _
) As FormulaIndia
'Usage
Dim instance As TaxDatabaseAccessor
Dim itemTaxGroupId As String
Dim taxCode As String
Dim columns As ColumnSet
Dim returnValue As FormulaIndia

returnValue = instance.GetTaxCodeFormulaIndia(itemTaxGroupId, _
    taxCode, columns)
```

``` csharp
public FormulaIndia GetTaxCodeFormulaIndia(
    string itemTaxGroupId,
    string taxCode,
    ColumnSet columns
)
```

``` c++
public:
FormulaIndia^ GetTaxCodeFormulaIndia(
    String^ itemTaxGroupId, 
    String^ taxCode, 
    ColumnSet^ columns
)
```

#### Parameters

  - itemTaxGroupId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - taxCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.FormulaIndia](formulaindia-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The tax code formula.  

## See Also

#### Reference

[TaxDatabaseAccessor Class](taxdatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


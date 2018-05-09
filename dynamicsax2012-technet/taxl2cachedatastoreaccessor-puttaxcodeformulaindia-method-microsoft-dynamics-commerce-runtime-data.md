---
title: TaxL2CacheDataStoreAccessor.PutTaxCodeFormulaIndia Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutTaxCodeFormulaIndia Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.TaxL2CacheDataStoreAccessor.PutTaxCodeFormulaIndia(System.String,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.FormulaIndia)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.taxl2cachedatastoreaccessor.puttaxcodeformulaindia(v=AX.60)
ms:contentKeyID: 62214235
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.TaxL2CacheDataStoreAccessor.PutTaxCodeFormulaIndia
dev_langs:
- CSharp
- C++
- VB
---

# PutTaxCodeFormulaIndia Method

Gets the tax code formula.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Sub PutTaxCodeFormulaIndia ( _
    itemTaxGroupId As String, _
    taxCode As String, _
    result As FormulaIndia _
)
'Usage
Dim instance As TaxL2CacheDataStoreAccessor
Dim itemTaxGroupId As String
Dim taxCode As String
Dim result As FormulaIndia

instance.PutTaxCodeFormulaIndia(itemTaxGroupId, _
    taxCode, result)
```

``` csharp
public void PutTaxCodeFormulaIndia(
    string itemTaxGroupId,
    string taxCode,
    FormulaIndia result
)
```

``` c++
public:
void PutTaxCodeFormulaIndia(
    String^ itemTaxGroupId, 
    String^ taxCode, 
    FormulaIndia^ result
)
```

#### Parameters

  - itemTaxGroupId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - taxCode  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - result  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.FormulaIndia](formulaindia-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[TaxL2CacheDataStoreAccessor Class](taxl2cachedatastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


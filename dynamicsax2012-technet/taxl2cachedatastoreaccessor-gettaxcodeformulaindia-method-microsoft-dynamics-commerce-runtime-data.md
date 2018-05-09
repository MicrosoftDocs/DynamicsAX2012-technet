---
title: TaxL2CacheDataStoreAccessor.GetTaxCodeFormulaIndia Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetTaxCodeFormulaIndia Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.TaxL2CacheDataStoreAccessor.GetTaxCodeFormulaIndia(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.taxl2cachedatastoreaccessor.gettaxcodeformulaindia(v=AX.60)
ms:contentKeyID: 62214955
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.TaxL2CacheDataStoreAccessor.GetTaxCodeFormulaIndia
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
    taxCode As String _
) As FormulaIndia
'Usage
Dim instance As TaxL2CacheDataStoreAccessor
Dim itemTaxGroupId As String
Dim taxCode As String
Dim returnValue As FormulaIndia

returnValue = instance.GetTaxCodeFormulaIndia(itemTaxGroupId, _
    taxCode)
```

``` csharp
public FormulaIndia GetTaxCodeFormulaIndia(
    string itemTaxGroupId,
    string taxCode
)
```

``` c++
public:
FormulaIndia^ GetTaxCodeFormulaIndia(
    String^ itemTaxGroupId, 
    String^ taxCode
)
```

#### Parameters

  - itemTaxGroupId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - taxCode  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.FormulaIndia](formulaindia-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
A collection of tax code intervals.  

## See Also

#### Reference

[TaxL2CacheDataStoreAccessor Class](taxl2cachedatastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


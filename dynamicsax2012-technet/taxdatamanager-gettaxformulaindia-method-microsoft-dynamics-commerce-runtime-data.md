---
title: TaxDataManager.GetTaxFormulaIndia Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetTaxFormulaIndia Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.TaxDataManager.GetTaxFormulaIndia(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.taxdatamanager.gettaxformulaindia(v=AX.60)
ms:contentKeyID: 62202991
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.TaxDataManager.GetTaxFormulaIndia
dev_langs:
- CSharp
- C++
- VB
---

# GetTaxFormulaIndia Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the tax code fomula for India.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetTaxFormulaIndia ( _
    itemTaxGroupId As String, _
    taxCode As String _
) As FormulaIndia
'Usage
Dim instance As TaxDataManager
Dim itemTaxGroupId As String
Dim taxCode As String
Dim returnValue As FormulaIndia

returnValue = instance.GetTaxFormulaIndia(itemTaxGroupId, _
    taxCode)
```

``` csharp
public FormulaIndia GetTaxFormulaIndia(
    string itemTaxGroupId,
    string taxCode
)
```

``` c++
public:
FormulaIndia^ GetTaxFormulaIndia(
    String^ itemTaxGroupId, 
    String^ taxCode
)
```

#### Parameters

  - itemTaxGroupId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - taxCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.FormulaIndia](formulaindia-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The formula of the tax code.  

## See Also

#### Reference

[TaxDataManager Class](taxdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


---
title: ITaxDataManager.GetTaxOverrideDetails Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetTaxOverrideDetails Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ITaxDataManager.GetTaxOverrideDetails(System.String,Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.itaxdatamanager.gettaxoverridedetails(v=AX.60)
ms:contentKeyID: 62204956
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ITaxDataManager.GetTaxOverrideDetails
dev_langs:
- CSharp
- C++
- VB
---

# GetTaxOverrideDetails Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the tax override details.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Function GetTaxOverrideDetails ( _
    taxOverrideCode As String, _
    columns As ColumnSet _
) As TaxOverride
'Usage
Dim instance As ITaxDataManager
Dim taxOverrideCode As String
Dim columns As ColumnSet
Dim returnValue As TaxOverride

returnValue = instance.GetTaxOverrideDetails(taxOverrideCode, _
    columns)
```

``` csharp
TaxOverride GetTaxOverrideDetails(
    string taxOverrideCode,
    ColumnSet columns
)
```

``` c++
TaxOverride^ GetTaxOverrideDetails(
    String^ taxOverrideCode, 
    ColumnSet^ columns
)
```

#### Parameters

  - taxOverrideCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxOverride](taxoverride-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Tax Override with the code given.  

## See Also

#### Reference

[ITaxDataManager Interface](itaxdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


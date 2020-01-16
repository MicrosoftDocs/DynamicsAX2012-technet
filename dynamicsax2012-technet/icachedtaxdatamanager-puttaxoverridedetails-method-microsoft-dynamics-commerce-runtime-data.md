---
title: ICachedTaxDataManager.PutTaxOverrideDetails Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutTaxOverrideDetails Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedTaxDataManager.PutTaxOverrideDetails(System.String,Microsoft.Dynamics.Commerce.Runtime.ColumnSet,Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxOverride)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.icachedtaxdatamanager.puttaxoverridedetails(v=AX.60)
ms:contentKeyID: 62204555
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedTaxDataManager.PutTaxOverrideDetails
dev_langs:
- CSharp
- C++
- VB
---

# PutTaxOverrideDetails Method

Stores the tax override details.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutTaxOverrideDetails ( _
    taxOverrideCode As String, _
    columns As ColumnSet, _
    result As TaxOverride _
)
'Usage
Dim instance As ICachedTaxDataManager
Dim taxOverrideCode As String
Dim columns As ColumnSet
Dim result As TaxOverride

instance.PutTaxOverrideDetails(taxOverrideCode, _
    columns, result)
```

``` csharp
void PutTaxOverrideDetails(
    string taxOverrideCode,
    ColumnSet columns,
    TaxOverride result
)
```

``` c++
void PutTaxOverrideDetails(
    String^ taxOverrideCode, 
    ColumnSet^ columns, 
    TaxOverride^ result
)
```

#### Parameters

  - taxOverrideCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - result  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxOverride](taxoverride-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ICachedTaxDataManager Interface](icachedtaxdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


---
title: TaxL2CacheDataStoreAccessor.GetTaxOverrideDetails Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetTaxOverrideDetails Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.TaxL2CacheDataStoreAccessor.GetTaxOverrideDetails(System.String,Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.taxl2cachedatastoreaccessor.gettaxoverridedetails(v=AX.60)
ms:contentKeyID: 62212570
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.TaxL2CacheDataStoreAccessor.GetTaxOverrideDetails
dev_langs:
- CSharp
- C++
- VB
---

# GetTaxOverrideDetails Method

Gets the tax override details.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetTaxOverrideDetails ( _
    taxOverrideCode As String, _
    columns As ColumnSet _
) As TaxOverride
'Usage
Dim instance As TaxL2CacheDataStoreAccessor
Dim taxOverrideCode As String
Dim columns As ColumnSet
Dim returnValue As TaxOverride

returnValue = instance.GetTaxOverrideDetails(taxOverrideCode, _
    columns)
```

``` csharp
public TaxOverride GetTaxOverrideDetails(
    string taxOverrideCode,
    ColumnSet columns
)
```

``` c++
public:
virtual TaxOverride^ GetTaxOverrideDetails(
    String^ taxOverrideCode, 
    ColumnSet^ columns
) sealed
```

#### Parameters

  - taxOverrideCode  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxOverride](taxoverride-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Tax Override with the code given.  

#### Implements

[ITaxDataManager.GetTaxOverrideDetails(String, ColumnSet)](itaxdatamanager-gettaxoverridedetails-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[TaxL2CacheDataStoreAccessor Class](taxl2cachedatastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


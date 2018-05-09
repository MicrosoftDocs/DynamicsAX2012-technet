---
title: IndiaTaxDataManager.GetTaxSummarySettingIndia Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetTaxSummarySettingIndia Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IndiaTaxDataManager.GetTaxSummarySettingIndia(Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.indiataxdatamanager.gettaxsummarysettingindia(v=AX.60)
ms:contentKeyID: 62213681
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IndiaTaxDataManager.GetTaxSummarySettingIndia
dev_langs:
- CSharp
- C++
- VB
---

# GetTaxSummarySettingIndia Method

Gets tax summary setting.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetTaxSummarySettingIndia ( _
    columns As ColumnSet _
) As TaxSummarySettingIndia
'Usage
Dim instance As IndiaTaxDataManager
Dim columns As ColumnSet
Dim returnValue As TaxSummarySettingIndia

returnValue = instance.GetTaxSummarySettingIndia(columns)
```

``` csharp
public TaxSummarySettingIndia GetTaxSummarySettingIndia(
    ColumnSet columns
)
```

``` c++
public:
TaxSummarySettingIndia^ GetTaxSummarySettingIndia(
    ColumnSet^ columns
)
```

#### Parameters

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxSummarySettingIndia](taxsummarysettingindia-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Tax summary setting.  

## See Also

#### Reference

[IndiaTaxDataManager Class](indiataxdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


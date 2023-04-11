---
title: TaxDataManager.GetTaxParameter Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetTaxParameter Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.TaxDataManager.GetTaxParameter(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.taxdatamanager.gettaxparameter(v=AX.60)
ms:contentKeyID: 65322750
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.TaxDataManager.GetTaxParameter
dev_langs:
- CSharp
- C++
- VB
---

# GetTaxParameter Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetTaxParameter ( _
    settings As QueryResultSettings _
) As TaxParameters
'Usage
Dim instance As TaxDataManager
Dim settings As QueryResultSettings
Dim returnValue As TaxParameters

returnValue = instance.GetTaxParameter(settings)
```

``` csharp
public TaxParameters GetTaxParameter(
    QueryResultSettings settings
)
```

``` c++
public:
TaxParameters^ GetTaxParameter(
    QueryResultSettings^ settings
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxParameters](taxparameters-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[TaxDataManager Class](taxdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


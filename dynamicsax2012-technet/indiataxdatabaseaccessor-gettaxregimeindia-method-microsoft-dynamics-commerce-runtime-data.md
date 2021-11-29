---
title: IndiaTaxDatabaseAccessor.GetTaxRegimeIndia Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetTaxRegimeIndia Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IndiaTaxDatabaseAccessor.GetTaxRegimeIndia(Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.indiataxdatabaseaccessor.gettaxregimeindia(v=AX.60)
ms:contentKeyID: 65319914
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IndiaTaxDatabaseAccessor.GetTaxRegimeIndia
dev_langs:
- CSharp
- C++
- VB
---

# GetTaxRegimeIndia Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetTaxRegimeIndia ( _
    columns As ColumnSet _
) As String
'Usage
Dim instance As IndiaTaxDatabaseAccessor
Dim columns As ColumnSet
Dim returnValue As String

returnValue = instance.GetTaxRegimeIndia(columns)
```

``` csharp
public string GetTaxRegimeIndia(
    ColumnSet columns
)
```

``` c++
public:
String^ GetTaxRegimeIndia(
    ColumnSet^ columns
)
```

#### Parameters

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[IndiaTaxDatabaseAccessor Class](indiataxdatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


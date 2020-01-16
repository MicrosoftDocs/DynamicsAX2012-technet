---
title: TillLayoutDataManager.ConvertToTillLayout Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: ConvertToTillLayout Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.TillLayoutDataManager.ConvertToTillLayout(Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataSet,System.TimeSpan)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.tilllayoutdatamanager.converttotilllayout(v=AX.60)
ms:contentKeyID: 65317862
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.TillLayoutDataManager.ConvertToTillLayout
dev_langs:
- CSharp
- C++
- VB
---

# ConvertToTillLayout Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Shared Function ConvertToTillLayout ( _
    ds As DataSet, _
    timeZoneOffset As TimeSpan _
) As TillLayout
'Usage
Dim ds As DataSet
Dim timeZoneOffset As TimeSpan
Dim returnValue As TillLayout

returnValue = TillLayoutDataManager.ConvertToTillLayout(ds, _
    timeZoneOffset)
```

``` csharp
public static TillLayout ConvertToTillLayout(
    DataSet ds,
    TimeSpan timeZoneOffset
)
```

``` c++
public:
static TillLayout^ ConvertToTillLayout(
    DataSet^ ds, 
    TimeSpan timeZoneOffset
)
```

#### Parameters

  - ds  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataSet](dataset-class-microsoft-dynamics-commerce-runtime-data-types.md)  

<!-- end list -->

  - timeZoneOffset  
    Type: [System.TimeSpan](https://technet.microsoft.com/library/269ew577\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TillLayout](tilllayout-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[TillLayoutDataManager Class](tilllayoutdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


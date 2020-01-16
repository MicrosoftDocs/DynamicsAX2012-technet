---
title: DataCacheAccessor.CalculateQuerySettingsHash Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: CalculateQuerySettingsHash Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DataCacheAccessor.CalculateQuerySettingsHash(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.datacacheaccessor.calculatequerysettingshash(v=AX.60)
ms:contentKeyID: 65320325
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DataCacheAccessor.CalculateQuerySettingsHash
dev_langs:
- CSharp
- C++
- VB
---

# CalculateQuerySettingsHash Method

Calculates the hash of a query setting object.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Protected Shared Function CalculateQuerySettingsHash ( _
    settings As QueryResultSettings _
) As Integer
'Usage
Dim settings As QueryResultSettings
Dim returnValue As Integer

returnValue = DataCacheAccessor.CalculateQuerySettingsHash(settings)
```

``` csharp
protected static int CalculateQuerySettingsHash(
    QueryResultSettings settings
)
```

``` c++
protected:
static int CalculateQuerySettingsHash(
    QueryResultSettings^ settings
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Hash corresponding to this query setting object.  

## See Also

#### Reference

[DataCacheAccessor Class](datacacheaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


---
title: ChargeL2CacheDataStoreAccessor.GetChargeDetails Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetChargeDetails Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ChargeL2CacheDataStoreAccessor.GetChargeDetails(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeModule,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.chargel2cachedatastoreaccessor.getchargedetails(v=AX.60)
ms:contentKeyID: 65319041
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ChargeL2CacheDataStoreAccessor.GetChargeDetails
dev_langs:
- CSharp
- C++
- VB
---

# GetChargeDetails Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the charge details.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetChargeDetails ( _
    chargeCode As String, _
    chargeModule As ChargeModule, _
    settings As QueryResultSettings _
) As ChargeLine
'Usage
Dim instance As ChargeL2CacheDataStoreAccessor
Dim chargeCode As String
Dim chargeModule As ChargeModule
Dim settings As QueryResultSettings
Dim returnValue As ChargeLine

returnValue = instance.GetChargeDetails(chargeCode, _
    chargeModule, settings)
```

``` csharp
public ChargeLine GetChargeDetails(
    string chargeCode,
    ChargeModule chargeModule,
    QueryResultSettings settings
)
```

``` c++
public:
virtual ChargeLine^ GetChargeDetails(
    String^ chargeCode, 
    ChargeModule chargeModule, 
    QueryResultSettings^ settings
) sealed
```

#### Parameters

  - chargeCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - chargeModule  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeModule](chargemodule-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeLine](chargeline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns the charge line with charge details populated.  

#### Implements

[ICachedChargeDataManager.GetChargeDetails(String, ChargeModule, QueryResultSettings)](icachedchargedatamanager-getchargedetails-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[ChargeL2CacheDataStoreAccessor Class](chargel2cachedatastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


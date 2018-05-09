---
title: ICachedChargeDataManager.PutChargeDetails Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutChargeDetails Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedChargeDataManager.PutChargeDetails(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeModule,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeLine)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.icachedchargedatamanager.putchargedetails(v=AX.60)
ms:contentKeyID: 65322966
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedChargeDataManager.PutChargeDetails
dev_langs:
- CSharp
- C++
- VB
---

# PutChargeDetails Method

Caches the charge details.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutChargeDetails ( _
    chargeCode As String, _
    chargeModule As ChargeModule, _
    settings As QueryResultSettings, _
    result As ChargeLine _
)
'Usage
Dim instance As ICachedChargeDataManager
Dim chargeCode As String
Dim chargeModule As ChargeModule
Dim settings As QueryResultSettings
Dim result As ChargeLine

instance.PutChargeDetails(chargeCode, _
    chargeModule, settings, result)
```

``` csharp
void PutChargeDetails(
    string chargeCode,
    ChargeModule chargeModule,
    QueryResultSettings settings,
    ChargeLine result
)
```

``` c++
void PutChargeDetails(
    String^ chargeCode, 
    ChargeModule chargeModule, 
    QueryResultSettings^ settings, 
    ChargeLine^ result
)
```

#### Parameters

  - chargeCode  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - chargeModule  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeModule](chargemodule-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - result  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeLine](chargeline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ICachedChargeDataManager Interface](icachedchargedatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


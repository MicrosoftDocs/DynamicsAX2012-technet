---
title: ChargeDataManager.GetChargeDetails Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetChargeDetails Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ChargeDataManager.GetChargeDetails(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeModule,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.chargedatamanager.getchargedetails(v=AX.60)
ms:contentKeyID: 65316591
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ChargeDataManager.GetChargeDetails
dev_langs:
- CSharp
- C++
- VB
---

# GetChargeDetails Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

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
Dim instance As ChargeDataManager
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

#### Implements

[IChargeDataManager.GetChargeDetails(String, ChargeModule, QueryResultSettings)](ichargedatamanager-getchargedetails-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[ChargeDataManager Class](chargedatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


---
title: ICurrencyV1.DetailedCurrencyInfo Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: DetailedCurrencyInfo Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICurrencyV1.DetailedCurrencyInfo(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.icurrencyv1.detailedcurrencyinfo(v=AX.60)
ms:contentKeyID: 47344028
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICurrencyV1.DetailedCurrencyInfo
dev_langs:
- CSharp
- C++
- VB
---

# DetailedCurrencyInfo Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Returns the ICurrencyInfo object.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function DetailedCurrencyInfo ( _
    currencyCode As String _
) As ICurrencyInfo
'Usage
Dim instance As ICurrencyV1
Dim currencyCode As String
Dim returnValue As ICurrencyInfo

returnValue = instance.DetailedCurrencyInfo(currencyCode)
```

``` csharp
ICurrencyInfo DetailedCurrencyInfo(
    string currencyCode
)
```

``` c++
ICurrencyInfo^ DetailedCurrencyInfo(
    String^ currencyCode
)
```

#### Parameters

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICurrencyInfo](icurrencyinfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
The ICurrencyInfo object.  

## See Also

#### Reference

[ICurrencyV1 Interface](icurrencyv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)


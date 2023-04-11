---
title: OrderManager.GetReturnOrderReasonCodes Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetReturnOrderReasonCodes Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetReturnOrderReasonCodes(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.ordermanager.getreturnorderreasoncodes(v=AX.60)
ms:contentKeyID: 65319353
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetReturnOrderReasonCodes
dev_langs:
- CSharp
- C++
- VB
---

# GetReturnOrderReasonCodes Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetReturnOrderReasonCodes ( _
    settings As QueryResultSettings _
) As IEnumerable(Of ReasonCode)
'Usage
Dim instance As OrderManager
Dim settings As QueryResultSettings
Dim returnValue As IEnumerable(Of ReasonCode)

returnValue = instance.GetReturnOrderReasonCodes(settings)
```

``` csharp
public IEnumerable<ReasonCode> GetReturnOrderReasonCodes(
    QueryResultSettings settings
)
```

``` c++
public:
IEnumerable<ReasonCode^>^ GetReturnOrderReasonCodes(
    QueryResultSettings^ settings
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ReasonCode](reasoncode-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)


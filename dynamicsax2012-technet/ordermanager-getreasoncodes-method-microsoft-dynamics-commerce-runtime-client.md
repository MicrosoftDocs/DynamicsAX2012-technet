---
title: OrderManager.GetReasonCodes Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetReasonCodes Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetReasonCodes(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.ordermanager.getreasoncodes(v=AX.60)
ms:contentKeyID: 65317357
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetReasonCodes
dev_langs:
- CSharp
- C++
- VB
---

# GetReasonCodes Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetReasonCodes ( _
    settings As QueryResultSettings _
) As PagedResult(Of ReasonCode)
'Usage
Dim instance As OrderManager
Dim settings As QueryResultSettings
Dim returnValue As PagedResult(Of ReasonCode)

returnValue = instance.GetReasonCodes(settings)
```

``` csharp
public PagedResult<ReasonCode> GetReasonCodes(
    QueryResultSettings settings
)
```

``` c++
public:
PagedResult<ReasonCode^>^ GetReasonCodes(
    QueryResultSettings^ settings
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[ReasonCode](reasoncode-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)


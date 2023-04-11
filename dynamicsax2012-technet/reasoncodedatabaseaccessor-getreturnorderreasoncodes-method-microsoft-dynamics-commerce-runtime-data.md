---
title: ReasonCodeDatabaseAccessor.GetReturnOrderReasonCodes Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetReturnOrderReasonCodes Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ReasonCodeDatabaseAccessor.GetReturnOrderReasonCodes(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.reasoncodedatabaseaccessor.getreturnorderreasoncodes(v=AX.60)
ms:contentKeyID: 65321428
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ReasonCodeDatabaseAccessor.GetReturnOrderReasonCodes
dev_langs:
- CSharp
- C++
- VB
---

# GetReturnOrderReasonCodes Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetReturnOrderReasonCodes ( _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of ReasonCode)
'Usage
Dim instance As ReasonCodeDatabaseAccessor
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of ReasonCode)

returnValue = instance.GetReturnOrderReasonCodes(settings)
```

``` csharp
public ReadOnlyCollection<ReasonCode> GetReturnOrderReasonCodes(
    QueryResultSettings settings
)
```

``` c++
public:
virtual ReadOnlyCollection<ReasonCode^>^ GetReturnOrderReasonCodes(
    QueryResultSettings^ settings
) sealed
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ReasonCode](reasoncode-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Implements

[IReasonCodeDataManager.GetReturnOrderReasonCodes(QueryResultSettings)](ireasoncodedatamanager-getreturnorderreasoncodes-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[ReasonCodeDatabaseAccessor Class](reasoncodedatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


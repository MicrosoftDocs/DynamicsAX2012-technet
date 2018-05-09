---
title: IReasonCodeDataManager.GetReturnOrderReasonCodes Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetReturnOrderReasonCodes Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IReasonCodeDataManager.GetReturnOrderReasonCodes(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.ireasoncodedatamanager.getreturnorderreasoncodes(v=AX.60)
ms:contentKeyID: 65321858
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IReasonCodeDataManager.GetReturnOrderReasonCodes
dev_langs:
- CSharp
- C++
- VB
---

# GetReturnOrderReasonCodes Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Function GetReturnOrderReasonCodes ( _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of ReasonCode)
'Usage
Dim instance As IReasonCodeDataManager
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of ReasonCode)

returnValue = instance.GetReturnOrderReasonCodes(settings)
```

``` csharp
ReadOnlyCollection<ReasonCode> GetReturnOrderReasonCodes(
    QueryResultSettings settings
)
```

``` c++
ReadOnlyCollection<ReasonCode^>^ GetReturnOrderReasonCodes(
    QueryResultSettings^ settings
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[ReasonCode](reasoncode-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[IReasonCodeDataManager Interface](ireasoncodedatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


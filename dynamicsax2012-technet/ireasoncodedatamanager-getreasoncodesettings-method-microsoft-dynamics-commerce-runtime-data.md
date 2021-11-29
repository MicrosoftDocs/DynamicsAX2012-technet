---
title: IReasonCodeDataManager.GetReasonCodeSettings Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetReasonCodeSettings Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IReasonCodeDataManager.GetReasonCodeSettings(Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.ireasoncodedatamanager.getreasoncodesettings(v=AX.60)
ms:contentKeyID: 62212685
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IReasonCodeDataManager.GetReasonCodeSettings
dev_langs:
- CSharp
- C++
- VB
---

# GetReasonCodeSettings Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the reason code settings for the current channel.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Function GetReasonCodeSettings ( _
    columns As ColumnSet _
) As ReasonCodeSettings
'Usage
Dim instance As IReasonCodeDataManager
Dim columns As ColumnSet
Dim returnValue As ReasonCodeSettings

returnValue = instance.GetReasonCodeSettings(columns)
```

``` csharp
ReasonCodeSettings GetReasonCodeSettings(
    ColumnSet columns
)
```

``` c++
ReasonCodeSettings^ GetReasonCodeSettings(
    ColumnSet^ columns
)
```

#### Parameters

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSettings](reasoncodesettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The reason code settings for the current channel.  

## See Also

#### Reference

[IReasonCodeDataManager Interface](ireasoncodedatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


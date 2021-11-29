---
title: ReasonCodeDataManager.GetReasonCodes Method (String, QueryResultSettings) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetReasonCodes Method (String, QueryResultSettings)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ReasonCodeDataManager.GetReasonCodes(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.reasoncodedatamanager.getreasoncodes(v=AX.60)
ms:contentKeyID: 65316486
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetReasonCodes Method (String, QueryResultSettings)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetReasonCodes ( _
    reasonCodeId As String, _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of ReasonCode)
'Usage
Dim instance As ReasonCodeDataManager
Dim reasonCodeId As String
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of ReasonCode)

returnValue = instance.GetReasonCodes(reasonCodeId, _
    settings)
```

``` csharp
public ReadOnlyCollection<ReasonCode> GetReasonCodes(
    string reasonCodeId,
    QueryResultSettings settings
)
```

``` c++
public:
ReadOnlyCollection<ReasonCode^>^ GetReasonCodes(
    String^ reasonCodeId, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - reasonCodeId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ReasonCode](reasoncode-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ReasonCodeDataManager Class](reasoncodedatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[GetReasonCodes Overload](reasoncodedatamanager-getreasoncodes-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


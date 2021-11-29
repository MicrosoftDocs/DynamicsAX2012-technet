---
title: ReasonCodeDatabaseAccessor.GetReasonCodes Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetReasonCodes Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ReasonCodeDatabaseAccessor.GetReasonCodes(System.String,System.String,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.reasoncodedatabaseaccessor.getreasoncodes(v=AX.60)
ms:contentKeyID: 65315684
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ReasonCodeDatabaseAccessor.GetReasonCodes
dev_langs:
- CSharp
- C++
- VB
---

# GetReasonCodes Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetReasonCodes ( _
    reasonCodeId As String, _
    channelLanguageId As String, _
    employeeLanguageId As String, _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of ReasonCode)
'Usage
Dim instance As ReasonCodeDatabaseAccessor
Dim reasonCodeId As String
Dim channelLanguageId As String
Dim employeeLanguageId As String
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of ReasonCode)

returnValue = instance.GetReasonCodes(reasonCodeId, _
    channelLanguageId, employeeLanguageId, _
    settings)
```

``` csharp
public ReadOnlyCollection<ReasonCode> GetReasonCodes(
    string reasonCodeId,
    string channelLanguageId,
    string employeeLanguageId,
    QueryResultSettings settings
)
```

``` c++
public:
virtual ReadOnlyCollection<ReasonCode^>^ GetReasonCodes(
    String^ reasonCodeId, 
    String^ channelLanguageId, 
    String^ employeeLanguageId, 
    QueryResultSettings^ settings
) sealed
```

#### Parameters

  - reasonCodeId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - channelLanguageId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - employeeLanguageId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ReasonCode](reasoncode-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Implements

[IReasonCodeDataManager.GetReasonCodes(String, String, String, QueryResultSettings)](ireasoncodedatamanager-getreasoncodes-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[ReasonCodeDatabaseAccessor Class](reasoncodedatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


---
title: ICachedReasonCodeDataManager.PutReasonSubCodes Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutReasonSubCodes Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedReasonCodeDataManager.PutReasonSubCodes(System.String,System.String,System.String,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonSubCode})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.icachedreasoncodedatamanager.putreasonsubcodes(v=AX.60)
ms:contentKeyID: 65320485
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedReasonCodeDataManager.PutReasonSubCodes
dev_langs:
- CSharp
- C++
- VB
---

# PutReasonSubCodes Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutReasonSubCodes ( _
    reasonCodeId As String, _
    reasonSubCodeId As String, _
    channelLanguageId As String, _
    employeeLanguageId As String, _
    settings As QueryResultSettings, _
    result As ReadOnlyCollection(Of ReasonSubCode) _
)
'Usage
Dim instance As ICachedReasonCodeDataManager
Dim reasonCodeId As String
Dim reasonSubCodeId As String
Dim channelLanguageId As String
Dim employeeLanguageId As String
Dim settings As QueryResultSettings
Dim result As ReadOnlyCollection(Of ReasonSubCode)

instance.PutReasonSubCodes(reasonCodeId, _
    reasonSubCodeId, channelLanguageId, _
    employeeLanguageId, settings, result)
```

``` csharp
void PutReasonSubCodes(
    string reasonCodeId,
    string reasonSubCodeId,
    string channelLanguageId,
    string employeeLanguageId,
    QueryResultSettings settings,
    ReadOnlyCollection<ReasonSubCode> result
)
```

``` c++
void PutReasonSubCodes(
    String^ reasonCodeId, 
    String^ reasonSubCodeId, 
    String^ channelLanguageId, 
    String^ employeeLanguageId, 
    QueryResultSettings^ settings, 
    ReadOnlyCollection<ReasonSubCode^>^ result
)
```

#### Parameters

  - reasonCodeId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - reasonSubCodeId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - channelLanguageId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - employeeLanguageId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - result  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[ReasonSubCode](reasonsubcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ICachedReasonCodeDataManager Interface](icachedreasoncodedatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


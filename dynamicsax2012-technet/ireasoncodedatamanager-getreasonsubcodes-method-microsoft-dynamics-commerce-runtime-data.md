---
title: IReasonCodeDataManager.GetReasonSubCodes Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetReasonSubCodes Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IReasonCodeDataManager.GetReasonSubCodes(System.String,System.String,System.String,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.ireasoncodedatamanager.getreasonsubcodes(v=AX.60)
ms:contentKeyID: 65322713
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IReasonCodeDataManager.GetReasonSubCodes
dev_langs:
- CSharp
- C++
- VB
---

# GetReasonSubCodes Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Function GetReasonSubCodes ( _
    reasonCodeId As String, _
    reasonSubCodeId As String, _
    channelLanguageId As String, _
    employeeLanguageId As String, _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of ReasonSubCode)
'Usage
Dim instance As IReasonCodeDataManager
Dim reasonCodeId As String
Dim reasonSubCodeId As String
Dim channelLanguageId As String
Dim employeeLanguageId As String
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of ReasonSubCode)

returnValue = instance.GetReasonSubCodes(reasonCodeId, _
    reasonSubCodeId, channelLanguageId, _
    employeeLanguageId, settings)
```

``` csharp
ReadOnlyCollection<ReasonSubCode> GetReasonSubCodes(
    string reasonCodeId,
    string reasonSubCodeId,
    string channelLanguageId,
    string employeeLanguageId,
    QueryResultSettings settings
)
```

``` c++
ReadOnlyCollection<ReasonSubCode^>^ GetReasonSubCodes(
    String^ reasonCodeId, 
    String^ reasonSubCodeId, 
    String^ channelLanguageId, 
    String^ employeeLanguageId, 
    QueryResultSettings^ settings
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

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[ReasonSubCode](reasonsubcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[IReasonCodeDataManager Interface](ireasoncodedatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


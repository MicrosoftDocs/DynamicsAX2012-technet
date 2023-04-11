---
title: ReasonCodeDataManager.GetReasonSubCodes Method (String, String, QueryResultSettings) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetReasonSubCodes Method (String, String, QueryResultSettings)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ReasonCodeDataManager.GetReasonSubCodes(System.String,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.reasoncodedatamanager.getreasonsubcodes(v=AX.60)
ms:contentKeyID: 65322428
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetReasonSubCodes Method (String, String, QueryResultSettings)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetReasonSubCodes ( _
    reasonCodeId As String, _
    reasonSubCodeId As String, _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of ReasonSubCode)
'Usage
Dim instance As ReasonCodeDataManager
Dim reasonCodeId As String
Dim reasonSubCodeId As String
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of ReasonSubCode)

returnValue = instance.GetReasonSubCodes(reasonCodeId, _
    reasonSubCodeId, settings)
```

``` csharp
public ReadOnlyCollection<ReasonSubCode> GetReasonSubCodes(
    string reasonCodeId,
    string reasonSubCodeId,
    QueryResultSettings settings
)
```

``` c++
public:
ReadOnlyCollection<ReasonSubCode^>^ GetReasonSubCodes(
    String^ reasonCodeId, 
    String^ reasonSubCodeId, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - reasonCodeId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - reasonSubCodeId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ReasonSubCode](reasonsubcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ReasonCodeDataManager Class](reasoncodedatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[GetReasonSubCodes Overload](reasoncodedatamanager-getreasonsubcodes-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


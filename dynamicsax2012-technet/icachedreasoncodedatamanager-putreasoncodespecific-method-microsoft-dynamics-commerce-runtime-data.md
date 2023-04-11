---
title: ICachedReasonCodeDataManager.PutReasonCodeSpecific Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutReasonCodeSpecific Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedReasonCodeDataManager.PutReasonCodeSpecific(Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeTableRefType,System.String,System.String,System.String,System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCode})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.icachedreasoncodedatamanager.putreasoncodespecific(v=AX.60)
ms:contentKeyID: 62210269
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedReasonCodeDataManager.PutReasonCodeSpecific
dev_langs:
- CSharp
- C++
- VB
---

# PutReasonCodeSpecific Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Caches the reason codes.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutReasonCodeSpecific ( _
    tableRefType As ReasonCodeTableRefType, _
    refRelation As String, _
    refRelation2 As String, _
    refRelation3 As String, _
    result As ReadOnlyCollection(Of ReasonCode) _
)
'Usage
Dim instance As ICachedReasonCodeDataManager
Dim tableRefType As ReasonCodeTableRefType
Dim refRelation As String
Dim refRelation2 As String
Dim refRelation3 As String
Dim result As ReadOnlyCollection(Of ReasonCode)

instance.PutReasonCodeSpecific(tableRefType, _
    refRelation, refRelation2, refRelation3, _
    result)
```

``` csharp
void PutReasonCodeSpecific(
    ReasonCodeTableRefType tableRefType,
    string refRelation,
    string refRelation2,
    string refRelation3,
    ReadOnlyCollection<ReasonCode> result
)
```

``` c++
void PutReasonCodeSpecific(
    ReasonCodeTableRefType tableRefType, 
    String^ refRelation, 
    String^ refRelation2, 
    String^ refRelation3, 
    ReadOnlyCollection<ReasonCode^>^ result
)
```

#### Parameters

  - tableRefType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeTableRefType](reasoncodetablereftype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - refRelation  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - refRelation2  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - refRelation3  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - result  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ReasonCode](reasoncode-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ICachedReasonCodeDataManager Interface](icachedreasoncodedatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


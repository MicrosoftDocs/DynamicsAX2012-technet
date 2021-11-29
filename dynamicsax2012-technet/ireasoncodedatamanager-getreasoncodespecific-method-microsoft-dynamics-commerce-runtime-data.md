---
title: IReasonCodeDataManager.GetReasonCodeSpecific Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetReasonCodeSpecific Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IReasonCodeDataManager.GetReasonCodeSpecific(Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeTableRefType,System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.ireasoncodedatamanager.getreasoncodespecific(v=AX.60)
ms:contentKeyID: 62212658
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IReasonCodeDataManager.GetReasonCodeSpecific
dev_langs:
- CSharp
- C++
- VB
---

# GetReasonCodeSpecific Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the entity specific reason code with given table information and keys.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Function GetReasonCodeSpecific ( _
    tableRefType As ReasonCodeTableRefType, _
    refRelation As String, _
    refRelation2 As String, _
    refRelation3 As String _
) As ReadOnlyCollection(Of ReasonCode)
'Usage
Dim instance As IReasonCodeDataManager
Dim tableRefType As ReasonCodeTableRefType
Dim refRelation As String
Dim refRelation2 As String
Dim refRelation3 As String
Dim returnValue As ReadOnlyCollection(Of ReasonCode)

returnValue = instance.GetReasonCodeSpecific(tableRefType, _
    refRelation, refRelation2, refRelation3)
```

``` csharp
ReadOnlyCollection<ReasonCode> GetReasonCodeSpecific(
    ReasonCodeTableRefType tableRefType,
    string refRelation,
    string refRelation2,
    string refRelation3
)
```

``` c++
ReadOnlyCollection<ReasonCode^>^ GetReasonCodeSpecific(
    ReasonCodeTableRefType tableRefType, 
    String^ refRelation, 
    String^ refRelation2, 
    String^ refRelation3
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

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ReasonCode](reasoncode-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The reason code (if any) that corresponds to the provided information.  

## See Also

#### Reference

[IReasonCodeDataManager Interface](ireasoncodedatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


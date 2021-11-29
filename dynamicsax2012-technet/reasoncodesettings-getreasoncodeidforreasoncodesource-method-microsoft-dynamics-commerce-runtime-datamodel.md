---
title: ReasonCodeSettings.GetReasonCodeIdForReasonCodeSource Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GetReasonCodeIdForReasonCodeSource Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSettings.GetReasonCodeIdForReasonCodeSource(Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSourceType)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncodesettings.getreasoncodeidforreasoncodesource(v=AX.60)
ms:contentKeyID: 62202640
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSettings.GetReasonCodeIdForReasonCodeSource
dev_langs:
- CSharp
- C++
- VB
---

# GetReasonCodeIdForReasonCodeSource Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the reason code id for reason code source.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Function GetReasonCodeIdForReasonCodeSource ( _
    reasonCodeSourceType As ReasonCodeSourceType _
) As String
'Usage
Dim instance As ReasonCodeSettings
Dim reasonCodeSourceType As ReasonCodeSourceType
Dim returnValue As String

returnValue = instance.GetReasonCodeIdForReasonCodeSource(reasonCodeSourceType)
```

``` csharp
public string GetReasonCodeIdForReasonCodeSource(
    ReasonCodeSourceType reasonCodeSourceType
)
```

``` c++
public:
String^ GetReasonCodeIdForReasonCodeSource(
    ReasonCodeSourceType reasonCodeSourceType
)
```

#### Parameters

  - reasonCodeSourceType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSourceType](reasoncodesourcetype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The reason code id.  

## See Also

#### Reference

[ReasonCodeSettings Class](reasoncodesettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


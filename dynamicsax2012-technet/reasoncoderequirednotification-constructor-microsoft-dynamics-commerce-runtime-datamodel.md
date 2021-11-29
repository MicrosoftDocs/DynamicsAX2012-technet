---
title: ReasonCodeRequiredNotification Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReasonCodeRequiredNotification Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeRequiredNotification.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCode},System.Collections.Generic.IEnumerable{System.String},System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeRequirement})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncoderequirednotification.reasoncoderequirednotification(v=AX.60)
ms:contentKeyID: 65322571
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeRequiredNotification.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# ReasonCodeRequiredNotification Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [ReasonCodeRequiredNotification](reasoncoderequirednotification-class-microsoft-dynamics-commerce-runtime-datamodel.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    requiredReasonCodes As IEnumerable(Of ReasonCode), _
    transactionRequiredReasonCodeIds As IEnumerable(Of String), _
    reasonCodeRequirements As IEnumerable(Of ReasonCodeRequirement) _
)
'Usage
Dim requiredReasonCodes As IEnumerable(Of ReasonCode)
Dim transactionRequiredReasonCodeIds As IEnumerable(Of String)
Dim reasonCodeRequirements As IEnumerable(Of ReasonCodeRequirement)

Dim instance As New ReasonCodeRequiredNotification(requiredReasonCodes, _
    transactionRequiredReasonCodeIds, _
    reasonCodeRequirements)
```

``` csharp
public ReasonCodeRequiredNotification(
    IEnumerable<ReasonCode> requiredReasonCodes,
    IEnumerable<string> transactionRequiredReasonCodeIds,
    IEnumerable<ReasonCodeRequirement> reasonCodeRequirements
)
```

``` c++
public:
ReasonCodeRequiredNotification(
    IEnumerable<ReasonCode^>^ requiredReasonCodes, 
    IEnumerable<String^>^ transactionRequiredReasonCodeIds, 
    IEnumerable<ReasonCodeRequirement^>^ reasonCodeRequirements
)
```

#### Parameters

  - requiredReasonCodes  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ReasonCode](reasoncode-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - transactionRequiredReasonCodeIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - reasonCodeRequirements  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ReasonCodeRequirement](reasoncoderequirement-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ReasonCodeRequiredNotification Class](reasoncoderequirednotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


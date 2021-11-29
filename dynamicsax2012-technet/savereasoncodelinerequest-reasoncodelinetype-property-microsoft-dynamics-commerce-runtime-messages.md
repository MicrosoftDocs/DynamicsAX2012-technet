---
title: SaveReasonCodeLineRequest.ReasonCodeLineType Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ReasonCodeLineType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.SaveReasonCodeLineRequest.ReasonCodeLineType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.savereasoncodelinerequest.reasoncodelinetype(v=AX.60)
ms:contentKeyID: 62212359
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.SaveReasonCodeLineRequest.ReasonCodeLineType
dev_langs:
- CSharp
- C++
- VB
---

# ReasonCodeLineType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the type of the reason code line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ReasonCodeLineType As ReasonCodeLineType
    Get
    Set
'Usage
Dim instance As SaveReasonCodeLineRequest
Dim value As ReasonCodeLineType

value = instance.ReasonCodeLineType

instance.ReasonCodeLineType = value
```

``` csharp
[DataMemberAttribute]
public ReasonCodeLineType ReasonCodeLineType { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property ReasonCodeLineType ReasonCodeLineType {
    ReasonCodeLineType get ();
    void set (ReasonCodeLineType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeLineType](reasoncodelinetype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ReasonCodeLineType](reasoncodelinetype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[SaveReasonCodeLineRequest Class](savereasoncodelinerequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


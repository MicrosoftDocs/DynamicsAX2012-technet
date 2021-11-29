---
title: SaveReasonCodeLineRequest.ReasonCodeLine Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ReasonCodeLine Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.SaveReasonCodeLineRequest.ReasonCodeLine
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.savereasoncodelinerequest.reasoncodeline(v=AX.60)
ms:contentKeyID: 62213555
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.SaveReasonCodeLineRequest.ReasonCodeLine
dev_langs:
- CSharp
- C++
- VB
---

# ReasonCodeLine Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the reason code line to add or update.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ReasonCodeLine As ReasonCodeLine
    Get
    Set
'Usage
Dim instance As SaveReasonCodeLineRequest
Dim value As ReasonCodeLine

value = instance.ReasonCodeLine

instance.ReasonCodeLine = value
```

``` csharp
[DataMemberAttribute]
public ReasonCodeLine ReasonCodeLine { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property ReasonCodeLine^ ReasonCodeLine {
    ReasonCodeLine^ get ();
    void set (ReasonCodeLine^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeLine](reasoncodeline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ReasonCodeLine](reasoncodeline-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[SaveReasonCodeLineRequest Class](savereasoncodelinerequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


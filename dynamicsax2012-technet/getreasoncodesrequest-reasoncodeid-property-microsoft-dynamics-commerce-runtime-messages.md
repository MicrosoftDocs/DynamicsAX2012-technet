---
title: GetReasonCodesRequest.ReasonCodeId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ReasonCodeId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetReasonCodesRequest.ReasonCodeId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getreasoncodesrequest.reasoncodeid(v=AX.60)
ms:contentKeyID: 62212673
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetReasonCodesRequest.ReasonCodeId
dev_langs:
- CSharp
- C++
- VB
---

# ReasonCodeId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the reason code identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ReasonCodeId As String
    Get
    Private Set
'Usage
Dim instance As GetReasonCodesRequest
Dim value As String

value = instance.ReasonCodeId
```

``` csharp
[DataMemberAttribute]
public string ReasonCodeId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ReasonCodeId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetReasonCodesRequest Class](getreasoncodesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


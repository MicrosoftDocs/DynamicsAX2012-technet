---
title: GetReasonCodesDataRequest.ReasonCodeId Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: ReasonCodeId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetReasonCodesDataRequest.ReasonCodeId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getreasoncodesdatarequest.reasoncodeid(v=AX.60)
ms:contentKeyID: 65321531
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetReasonCodesDataRequest.ReasonCodeId
dev_langs:
- CSharp
- C++
- VB
---

# ReasonCodeId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the reason code identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property ReasonCodeId As String
    Get
    Private Set
'Usage
Dim instance As GetReasonCodesDataRequest
Dim value As String

value = instance.ReasonCodeId
```

``` csharp
public string ReasonCodeId { get; private set; }
```

``` c++
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

[GetReasonCodesDataRequest Class](getreasoncodesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


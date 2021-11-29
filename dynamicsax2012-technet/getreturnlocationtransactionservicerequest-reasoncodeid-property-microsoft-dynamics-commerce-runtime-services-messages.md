---
title: GetReturnLocationTransactionServiceRequest.ReasonCodeId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ReasonCodeId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReturnLocationTransactionServiceRequest.ReasonCodeId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getreturnlocationtransactionservicerequest.reasoncodeid(v=AX.60)
ms:contentKeyID: 65317750
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReturnLocationTransactionServiceRequest.ReasonCodeId
dev_langs:
- CSharp
- C++
- VB
---

# ReasonCodeId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ReasonCodeId As String
    Get
    Private Set
'Usage
Dim instance As GetReturnLocationTransactionServiceRequest
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

## See Also

#### Reference

[GetReturnLocationTransactionServiceRequest Class](getreturnlocationtransactionservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


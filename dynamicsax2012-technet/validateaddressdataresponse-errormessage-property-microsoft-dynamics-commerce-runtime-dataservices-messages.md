---
title: ValidateAddressDataResponse.ErrorMessage Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: ErrorMessage Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ValidateAddressDataResponse.ErrorMessage
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.validateaddressdataresponse.errormessage(v=AX.60)
ms:contentKeyID: 65318583
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ValidateAddressDataResponse.ErrorMessage
dev_langs:
- CSharp
- C++
- VB
---

# ErrorMessage Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the error message.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ErrorMessage As String
    Get
    Private Set
'Usage
Dim instance As ValidateAddressDataResponse
Dim value As String

value = instance.ErrorMessage
```

``` csharp
[DataMemberAttribute]
public string ErrorMessage { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ErrorMessage {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ValidateAddressDataResponse Class](validateaddressdataresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


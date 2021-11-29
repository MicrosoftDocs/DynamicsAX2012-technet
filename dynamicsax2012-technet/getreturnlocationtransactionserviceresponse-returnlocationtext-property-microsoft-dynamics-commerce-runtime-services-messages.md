---
title: GetReturnLocationTransactionServiceResponse.ReturnLocationText Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ReturnLocationText Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReturnLocationTransactionServiceResponse.ReturnLocationText
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getreturnlocationtransactionserviceresponse.returnlocationtext(v=AX.60)
ms:contentKeyID: 65316697
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReturnLocationTransactionServiceResponse.ReturnLocationText
dev_langs:
- CSharp
- C++
- VB
---

# ReturnLocationText Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ReturnLocationText As String
    Get
    Private Set
'Usage
Dim instance As GetReturnLocationTransactionServiceResponse
Dim value As String

value = instance.ReturnLocationText
```

``` csharp
[DataMemberAttribute]
public string ReturnLocationText { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ReturnLocationText {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[GetReturnLocationTransactionServiceResponse Class](getreturnlocationtransactionserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


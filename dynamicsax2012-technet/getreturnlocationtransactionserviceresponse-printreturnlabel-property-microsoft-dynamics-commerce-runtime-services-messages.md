---
title: GetReturnLocationTransactionServiceResponse.PrintReturnLabel Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: PrintReturnLabel Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReturnLocationTransactionServiceResponse.PrintReturnLabel
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getreturnlocationtransactionserviceresponse.printreturnlabel(v=AX.60)
ms:contentKeyID: 65318970
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReturnLocationTransactionServiceResponse.PrintReturnLabel
dev_langs:
- CSharp
- C++
- VB
---

# PrintReturnLabel Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PrintReturnLabel As Boolean
    Get
    Private Set
'Usage
Dim instance As GetReturnLocationTransactionServiceResponse
Dim value As Boolean

value = instance.PrintReturnLabel
```

``` csharp
[DataMemberAttribute]
public bool PrintReturnLabel { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property bool PrintReturnLabel {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[GetReturnLocationTransactionServiceResponse Class](getreturnlocationtransactionserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


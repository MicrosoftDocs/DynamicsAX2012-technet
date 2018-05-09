---
title: GetReturnLocationTransactionServiceRequest.Line Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Line Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReturnLocationTransactionServiceRequest.Line
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getreturnlocationtransactionservicerequest.line(v=AX.60)
ms:contentKeyID: 65319920
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReturnLocationTransactionServiceRequest.Line
dev_langs:
- CSharp
- C++
- VB
---

# Line Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Line As SalesLine
    Get
    Private Set
'Usage
Dim instance As GetReturnLocationTransactionServiceRequest
Dim value As SalesLine

value = instance.Line
```

``` csharp
[DataMemberAttribute]
public SalesLine Line { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property SalesLine^ Line {
    SalesLine^ get ();
    private: void set (SalesLine^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetReturnLocationTransactionServiceRequest Class](getreturnlocationtransactionservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


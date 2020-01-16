---
title: GetTransferOrderRequest.OrderId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: OrderId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetTransferOrderRequest.OrderId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.gettransferorderrequest.orderid(v=AX.60)
ms:contentKeyID: 62204321
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetTransferOrderRequest.OrderId
dev_langs:
- CSharp
- C++
- VB
---

# OrderId Property

Gets or sets the order identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property OrderId As String
    Get
    Set
'Usage
Dim instance As GetTransferOrderRequest
Dim value As String

value = instance.OrderId

instance.OrderId = value
```

``` csharp
[DataMemberAttribute]
public string OrderId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ OrderId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetTransferOrderRequest Class](gettransferorderrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


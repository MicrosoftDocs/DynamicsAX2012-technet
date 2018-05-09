---
title: GetPurchaseOrderDataRequest.OrderId Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: OrderId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPurchaseOrderDataRequest.OrderId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getpurchaseorderdatarequest.orderid(v=AX.60)
ms:contentKeyID: 65321339
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPurchaseOrderDataRequest.OrderId
dev_langs:
- CSharp
- C++
- VB
---

# OrderId Property

Gets the order identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property OrderId As String
    Get
    Private Set
'Usage
Dim instance As GetPurchaseOrderDataRequest
Dim value As String

value = instance.OrderId
```

``` csharp
[DataMemberAttribute]
public string OrderId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ OrderId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetPurchaseOrderDataRequest Class](getpurchaseorderdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


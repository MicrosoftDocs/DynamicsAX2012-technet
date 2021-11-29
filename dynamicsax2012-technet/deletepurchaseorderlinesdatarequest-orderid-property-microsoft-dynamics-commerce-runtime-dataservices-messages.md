---
title: DeletePurchaseOrderLinesDataRequest.OrderId Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: OrderId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.DeletePurchaseOrderLinesDataRequest.OrderId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.deletepurchaseorderlinesdatarequest.orderid(v=AX.60)
ms:contentKeyID: 65320597
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.DeletePurchaseOrderLinesDataRequest.OrderId
dev_langs:
- CSharp
- C++
- VB
---

# OrderId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the id of the order.

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
Dim instance As DeletePurchaseOrderLinesDataRequest
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

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[DeletePurchaseOrderLinesDataRequest Class](deletepurchaseorderlinesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


---
title: UploadOrderRequest.Order Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Order Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.UploadOrderRequest.Order
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.uploadorderrequest.order(v=AX.60)
ms:contentKeyID: 62212052
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.UploadOrderRequest.Order
dev_langs:
- CSharp
- C++
- VB
---

# Order Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the sales orders.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Order As SalesOrder
    Get
    Set
'Usage
Dim instance As UploadOrderRequest
Dim value As SalesOrder

value = instance.Order

instance.Order = value
```

``` csharp
[DataMemberAttribute]
public SalesOrder Order { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property SalesOrder^ Order {
    SalesOrder^ get ();
    void set (SalesOrder^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrder](salesorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [SalesOrder](salesorder-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[UploadOrderRequest Class](uploadorderrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


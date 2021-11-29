---
title: GetInvoiceServiceResponse.Order Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Order Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetInvoiceServiceResponse.Order
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getinvoiceserviceresponse.order(v=AX.60)
ms:contentKeyID: 62209046
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetInvoiceServiceResponse.Order
dev_langs:
- CSharp
- C++
- VB
---

# Order Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the order.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Order As SalesOrder
    Get
    Private Set
'Usage
Dim instance As GetInvoiceServiceResponse
Dim value As SalesOrder

value = instance.Order
```

``` csharp
[DataMemberAttribute]
public SalesOrder Order { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property SalesOrder^ Order {
    SalesOrder^ get ();
    private: void set (SalesOrder^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrder](salesorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [SalesOrder](salesorder-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetInvoiceServiceResponse Class](getinvoiceserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


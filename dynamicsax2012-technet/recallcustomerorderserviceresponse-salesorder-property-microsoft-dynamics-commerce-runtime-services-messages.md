---
title: RecallCustomerOrderServiceResponse.SalesOrder Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: SalesOrder Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.RecallCustomerOrderServiceResponse.SalesOrder
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.recallcustomerorderserviceresponse.salesorder(v=AX.60)
ms:contentKeyID: 62214751
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.RecallCustomerOrderServiceResponse.SalesOrder
dev_langs:
- CSharp
- C++
- VB
---

# SalesOrder Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the cart.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property SalesOrder As SalesOrder
    Get
    Private Set
'Usage
Dim instance As RecallCustomerOrderServiceResponse
Dim value As SalesOrder

value = instance.SalesOrder
```

``` csharp
public SalesOrder SalesOrder { get; private set; }
```

``` c++
public:
property SalesOrder^ SalesOrder {
    SalesOrder^ get ();
    private: void set (SalesOrder^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrder](salesorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [SalesOrder](salesorder-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[RecallCustomerOrderServiceResponse Class](recallcustomerorderserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


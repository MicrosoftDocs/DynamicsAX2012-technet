---
title: CustomerOrderInfo.FromXml Method  (Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder)
TOCTitle: FromXml Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.CustomerOrderInfo.FromXml(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.customerorder.customerorderinfo.fromxml(v=AX.60)
ms:contentKeyID: 62213887
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.CustomerOrderInfo.FromXml
dev_langs:
- CSharp
- C++
- VB
---

# FromXml Method

Deserializes the customer order information from the specified XML blob.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Shared Function FromXml ( _
    orderXml As String _
) As CustomerOrderInfo
'Usage
Dim orderXml As String
Dim returnValue As CustomerOrderInfo

returnValue = CustomerOrderInfo.FromXml(orderXml)
```

``` csharp
public static CustomerOrderInfo FromXml(
    string orderXml
)
```

``` c++
public:
static CustomerOrderInfo^ FromXml(
    String^ orderXml
)
```

#### Parameters

  - orderXml  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.CustomerOrderInfo](customerorderinfo-class-microsoft-dynamics-commerce-runtime-services-customerorder.md)  
The customer order information.  

## See Also

#### Reference

[CustomerOrderInfo Class](customerorderinfo-class-microsoft-dynamics-commerce-runtime-services-customerorder.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder Namespace](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)


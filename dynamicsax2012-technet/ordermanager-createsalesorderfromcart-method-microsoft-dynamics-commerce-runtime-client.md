---
title: OrderManager.CreateSalesOrderFromCart Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: CreateSalesOrderFromCart Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.CreateSalesOrderFromCart(System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.ordermanager.createsalesorderfromcart(v=AX.60)
ms:contentKeyID: 65320941
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.CreateSalesOrderFromCart
dev_langs:
- CSharp
- C++
- VB
---

# CreateSalesOrderFromCart Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function CreateSalesOrderFromCart ( _
    cartId As String, _
    receiptEmail As String, _
    receiptNumberSequence As String _
) As SalesOrder
'Usage
Dim instance As OrderManager
Dim cartId As String
Dim receiptEmail As String
Dim receiptNumberSequence As String
Dim returnValue As SalesOrder

returnValue = instance.CreateSalesOrderFromCart(cartId, _
    receiptEmail, receiptNumberSequence)
```

``` csharp
public SalesOrder CreateSalesOrderFromCart(
    string cartId,
    string receiptEmail,
    string receiptNumberSequence
)
```

``` c++
public:
SalesOrder^ CreateSalesOrderFromCart(
    String^ cartId, 
    String^ receiptEmail, 
    String^ receiptNumberSequence
)
```

#### Parameters

  - cartId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - receiptEmail  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - receiptNumberSequence  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrder](salesorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)


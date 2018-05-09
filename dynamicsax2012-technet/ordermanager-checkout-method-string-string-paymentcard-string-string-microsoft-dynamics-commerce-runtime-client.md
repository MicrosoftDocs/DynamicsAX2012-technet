---
title: OrderManager.Checkout Method (String, String, PaymentCard, String, String) (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: Checkout Method (String, String, PaymentCard, String, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.Checkout(System.String,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCard,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.ordermanager.checkout(v=AX.60)
ms:contentKeyID: 65319230
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Checkout Method (String, String, PaymentCard, String, String)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function Checkout ( _
    key As String, _
    receiptEmail As String, _
    paymentCard As PaymentCard, _
    cardTypeId As String, _
    receiptNumberSequence As String _
) As SalesOrder
'Usage
Dim instance As OrderManager
Dim key As String
Dim receiptEmail As String
Dim paymentCard As PaymentCard
Dim cardTypeId As String
Dim receiptNumberSequence As String
Dim returnValue As SalesOrder

returnValue = instance.Checkout(key, receiptEmail, _
    paymentCard, cardTypeId, receiptNumberSequence)
```

``` csharp
public SalesOrder Checkout(
    string key,
    string receiptEmail,
    PaymentCard paymentCard,
    string cardTypeId,
    string receiptNumberSequence
)
```

``` c++
public:
SalesOrder^ Checkout(
    String^ key, 
    String^ receiptEmail, 
    PaymentCard^ paymentCard, 
    String^ cardTypeId, 
    String^ receiptNumberSequence
)
```

#### Parameters

  - key  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - receiptEmail  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - paymentCard  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCard](paymentcard-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - cardTypeId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - receiptNumberSequence  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrder](salesorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Checkout Overload](ordermanager-checkout-method-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)


---
title: OrderManager.SaveCustomerOrder Method (String, String, TokenizedPaymentCard, String, String) (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: SaveCustomerOrder Method (String, String, TokenizedPaymentCard, String, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.SaveCustomerOrder(System.String,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.TokenizedPaymentCard,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.ordermanager.savecustomerorder(v=AX.60)
ms:contentKeyID: 65315759
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SaveCustomerOrder Method (String, String, TokenizedPaymentCard, String, String)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function SaveCustomerOrder ( _
    cartId As String, _
    receiptEmail As String, _
    tokenizedPaymentCard As TokenizedPaymentCard, _
    cardTypeId As String, _
    receiptNumberSequence As String _
) As SalesOrder
'Usage
Dim instance As OrderManager
Dim cartId As String
Dim receiptEmail As String
Dim tokenizedPaymentCard As TokenizedPaymentCard
Dim cardTypeId As String
Dim receiptNumberSequence As String
Dim returnValue As SalesOrder

returnValue = instance.SaveCustomerOrder(cartId, _
    receiptEmail, tokenizedPaymentCard, _
    cardTypeId, receiptNumberSequence)
```

``` csharp
public SalesOrder SaveCustomerOrder(
    string cartId,
    string receiptEmail,
    TokenizedPaymentCard tokenizedPaymentCard,
    string cardTypeId,
    string receiptNumberSequence
)
```

``` c++
public:
SalesOrder^ SaveCustomerOrder(
    String^ cartId, 
    String^ receiptEmail, 
    TokenizedPaymentCard^ tokenizedPaymentCard, 
    String^ cardTypeId, 
    String^ receiptNumberSequence
)
```

#### Parameters

  - cartId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - receiptEmail  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - tokenizedPaymentCard  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TokenizedPaymentCard](tokenizedpaymentcard-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

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

[SaveCustomerOrder Overload](ordermanager-savecustomerorder-method-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)


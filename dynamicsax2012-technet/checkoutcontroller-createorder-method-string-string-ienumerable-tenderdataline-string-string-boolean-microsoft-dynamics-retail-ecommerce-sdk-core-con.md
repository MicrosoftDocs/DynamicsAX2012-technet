---
title: CheckoutController.CreateOrder Method (String, String, IEnumerable(TenderDataLine), String, String, Boolean) (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: CreateOrder Method (String, String, IEnumerable(TenderDataLine), String, String, Boolean)
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CheckoutController.CreateOrder(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.TenderDataLine},System.String,System.String,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.checkoutcontroller.createorder(v=AX.60)
ms:contentKeyID: 65318369
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CreateOrder Method (String, String, IEnumerable(TenderDataLine), String, String, Boolean)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function CreateOrder ( _
    shoppingCartId As String, _
    customerId As String, _
    tenderDataLines As IEnumerable(Of TenderDataLine), _
    emailAddress As String, _
    userName As String, _
    addAddressesToCustomer As Boolean _
) As String
'Usage
Dim instance As CheckoutController
Dim shoppingCartId As String
Dim customerId As String
Dim tenderDataLines As IEnumerable(Of TenderDataLine)
Dim emailAddress As String
Dim userName As String
Dim addAddressesToCustomer As Boolean
Dim returnValue As String

returnValue = instance.CreateOrder(shoppingCartId, _
    customerId, tenderDataLines, emailAddress, _
    userName, addAddressesToCustomer)
```

``` csharp
public virtual string CreateOrder(
    string shoppingCartId,
    string customerId,
    IEnumerable<TenderDataLine> tenderDataLines,
    string emailAddress,
    string userName,
    bool addAddressesToCustomer
)
```

``` c++
public:
virtual String^ CreateOrder(
    String^ shoppingCartId, 
    String^ customerId, 
    IEnumerable<TenderDataLine^>^ tenderDataLines, 
    String^ emailAddress, 
    String^ userName, 
    bool addAddressesToCustomer
)
```

#### Parameters

  - shoppingCartId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - customerId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - tenderDataLines  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[TenderDataLine](tenderdataline-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

<!-- end list -->

  - emailAddress  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - userName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - addAddressesToCustomer  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[CheckoutController Class](checkoutcontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[CreateOrder Overload](checkoutcontroller-createorder-method-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)


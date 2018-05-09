---
title: OrderManager.AddTenderLine Method (String, TenderLine) (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: AddTenderLine Method (String, TenderLine)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.AddTenderLine(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLine)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.ordermanager.addtenderline(v=AX.60)
ms:contentKeyID: 65315544
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# AddTenderLine Method (String, TenderLine)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function AddTenderLine ( _
    cartId As String, _
    preprocessedTenderLine As TenderLine _
) As Cart
'Usage
Dim instance As OrderManager
Dim cartId As String
Dim preprocessedTenderLine As TenderLine
Dim returnValue As Cart

returnValue = instance.AddTenderLine(cartId, _
    preprocessedTenderLine)
```

``` csharp
public Cart AddTenderLine(
    string cartId,
    TenderLine preprocessedTenderLine
)
```

``` c++
public:
Cart^ AddTenderLine(
    String^ cartId, 
    TenderLine^ preprocessedTenderLine
)
```

#### Parameters

  - cartId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - preprocessedTenderLine  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLine](tenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[AddTenderLine Overload](ordermanager-addtenderline-method-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)


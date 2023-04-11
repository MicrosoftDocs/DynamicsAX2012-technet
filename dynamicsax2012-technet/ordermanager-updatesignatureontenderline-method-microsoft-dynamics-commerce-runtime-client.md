---
title: OrderManager.UpdateSignatureOnTenderLine Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: UpdateSignatureOnTenderLine Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.UpdateSignatureOnTenderLine(System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.ordermanager.updatesignatureontenderline(v=AX.60)
ms:contentKeyID: 62213048
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.UpdateSignatureOnTenderLine
dev_langs:
- CSharp
- C++
- VB
---

# UpdateSignatureOnTenderLine Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Updates the tender line with signature.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function UpdateSignatureOnTenderLine ( _
    cartId As String, _
    tenderLineId As String, _
    signatureData As String _
) As Cart
'Usage
Dim instance As OrderManager
Dim cartId As String
Dim tenderLineId As String
Dim signatureData As String
Dim returnValue As Cart

returnValue = instance.UpdateSignatureOnTenderLine(cartId, _
    tenderLineId, signatureData)
```

``` csharp
public Cart UpdateSignatureOnTenderLine(
    string cartId,
    string tenderLineId,
    string signatureData
)
```

``` c++
public:
Cart^ UpdateSignatureOnTenderLine(
    String^ cartId, 
    String^ tenderLineId, 
    String^ signatureData
)
```

#### Parameters

  - cartId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - tenderLineId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - signatureData  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The updated cart.  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)


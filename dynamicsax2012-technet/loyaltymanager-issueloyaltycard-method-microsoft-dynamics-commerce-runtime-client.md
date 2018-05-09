---
title: LoyaltyManager.IssueLoyaltyCard Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: IssueLoyaltyCard Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.LoyaltyManager.IssueLoyaltyCard(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.loyaltymanager.issueloyaltycard(v=AX.60)
ms:contentKeyID: 62212288
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.LoyaltyManager.IssueLoyaltyCard
dev_langs:
- CSharp
- C++
- VB
---

# IssueLoyaltyCard Method

Issues a new loyalty card.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function IssueLoyaltyCard ( _
    loyaltyCardNumber As String, _
    customerAccountNumber As String _
) As LoyaltyCard
'Usage
Dim instance As LoyaltyManager
Dim loyaltyCardNumber As String
Dim customerAccountNumber As String
Dim returnValue As LoyaltyCard

returnValue = instance.IssueLoyaltyCard(loyaltyCardNumber, _
    customerAccountNumber)
```

``` csharp
public LoyaltyCard IssueLoyaltyCard(
    string loyaltyCardNumber,
    string customerAccountNumber
)
```

``` c++
public:
LoyaltyCard^ IssueLoyaltyCard(
    String^ loyaltyCardNumber, 
    String^ customerAccountNumber
)
```

#### Parameters

  - loyaltyCardNumber  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - customerAccountNumber  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCard](loyaltycard-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The newly issued card.  

## See Also

#### Reference

[LoyaltyManager Class](loyaltymanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)


---
title: LoyaltyManager.GetCustomerLoyaltyCards Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetCustomerLoyaltyCards Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.LoyaltyManager.GetCustomerLoyaltyCards(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.loyaltymanager.getcustomerloyaltycards(v=AX.60)
ms:contentKeyID: 62210485
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.LoyaltyManager.GetCustomerLoyaltyCards
dev_langs:
- CSharp
- C++
- VB
---

# GetCustomerLoyaltyCards Method

Gets the loyalty cards of the given customer.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetCustomerLoyaltyCards ( _
    customerAccountNumber As String _
) As ReadOnlyCollection(Of LoyaltyCard)
'Usage
Dim instance As LoyaltyManager
Dim customerAccountNumber As String
Dim returnValue As ReadOnlyCollection(Of LoyaltyCard)

returnValue = instance.GetCustomerLoyaltyCards(customerAccountNumber)
```

``` csharp
public ReadOnlyCollection<LoyaltyCard> GetCustomerLoyaltyCards(
    string customerAccountNumber
)
```

``` c++
public:
ReadOnlyCollection<LoyaltyCard^>^ GetCustomerLoyaltyCards(
    String^ customerAccountNumber
)
```

#### Parameters

  - customerAccountNumber  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[LoyaltyCard](loyaltycard-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The collection of loyalty cards.  

## See Also

#### Reference

[LoyaltyManager Class](loyaltymanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)


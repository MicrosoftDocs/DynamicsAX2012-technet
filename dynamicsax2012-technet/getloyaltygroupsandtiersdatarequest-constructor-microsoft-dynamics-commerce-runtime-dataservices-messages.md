---
title: GetLoyaltyGroupsAndTiersDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetLoyaltyGroupsAndTiersDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetLoyaltyGroupsAndTiersDataRequest.#ctor(System.String,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getloyaltygroupsandtiersdatarequest.getloyaltygroupsandtiersdatarequest(v=AX.60)
ms:contentKeyID: 65321334
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetLoyaltyGroupsAndTiersDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetLoyaltyGroupsAndTiersDataRequest Constructor

Initializes a new instance of the [GetLoyaltyGroupsAndTiersDataRequest](getloyaltygroupsandtiersdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    loyaltyCardNumber As String, _
    retrieveFutureLoyaltyCardTiers As Boolean _
)
'Usage
Dim loyaltyCardNumber As String
Dim retrieveFutureLoyaltyCardTiers As Boolean

Dim instance As New GetLoyaltyGroupsAndTiersDataRequest(loyaltyCardNumber, _
    retrieveFutureLoyaltyCardTiers)
```

``` csharp
public GetLoyaltyGroupsAndTiersDataRequest(
    string loyaltyCardNumber,
    bool retrieveFutureLoyaltyCardTiers
)
```

``` c++
public:
GetLoyaltyGroupsAndTiersDataRequest(
    String^ loyaltyCardNumber, 
    bool retrieveFutureLoyaltyCardTiers
)
```

#### Parameters

  - loyaltyCardNumber  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - retrieveFutureLoyaltyCardTiers  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[GetLoyaltyGroupsAndTiersDataRequest Class](getloyaltygroupsandtiersdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


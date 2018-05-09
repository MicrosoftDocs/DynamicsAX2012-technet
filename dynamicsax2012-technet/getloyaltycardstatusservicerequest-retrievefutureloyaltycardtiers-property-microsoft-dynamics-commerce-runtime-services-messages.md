---
title: GetLoyaltyCardStatusServiceRequest.RetrieveFutureLoyaltyCardTiers Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: RetrieveFutureLoyaltyCardTiers Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetLoyaltyCardStatusServiceRequest.RetrieveFutureLoyaltyCardTiers
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getloyaltycardstatusservicerequest.retrievefutureloyaltycardtiers(v=AX.60)
ms:contentKeyID: 62213837
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetLoyaltyCardStatusServiceRequest.RetrieveFutureLoyaltyCardTiers
dev_langs:
- CSharp
- C++
- VB
---

# RetrieveFutureLoyaltyCardTiers Property

Gets or sets a value indicating whether to retrieve the loyalty card tiers that take effect in the future.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property RetrieveFutureLoyaltyCardTiers As Boolean
    Get
    Set
'Usage
Dim instance As GetLoyaltyCardStatusServiceRequest
Dim value As Boolean

value = instance.RetrieveFutureLoyaltyCardTiers

instance.RetrieveFutureLoyaltyCardTiers = value
```

``` csharp
[DataMemberAttribute]
public bool RetrieveFutureLoyaltyCardTiers { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool RetrieveFutureLoyaltyCardTiers {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[GetLoyaltyCardStatusServiceRequest Class](getloyaltycardstatusservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


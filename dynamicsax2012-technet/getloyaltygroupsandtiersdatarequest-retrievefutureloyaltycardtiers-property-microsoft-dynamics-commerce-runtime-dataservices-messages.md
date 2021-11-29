---
title: GetLoyaltyGroupsAndTiersDataRequest.RetrieveFutureLoyaltyCardTiers Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: RetrieveFutureLoyaltyCardTiers Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetLoyaltyGroupsAndTiersDataRequest.RetrieveFutureLoyaltyCardTiers
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getloyaltygroupsandtiersdatarequest.retrievefutureloyaltycardtiers(v=AX.60)
ms:contentKeyID: 65319820
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetLoyaltyGroupsAndTiersDataRequest.RetrieveFutureLoyaltyCardTiers
dev_langs:
- CSharp
- C++
- VB
---

# RetrieveFutureLoyaltyCardTiers Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether to retrieve the loyalty card tiers that take effect in the future.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property RetrieveFutureLoyaltyCardTiers As Boolean
    Get
    Private Set
'Usage
Dim instance As GetLoyaltyGroupsAndTiersDataRequest
Dim value As Boolean

value = instance.RetrieveFutureLoyaltyCardTiers
```

``` csharp
[DataMemberAttribute]
public bool RetrieveFutureLoyaltyCardTiers { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property bool RetrieveFutureLoyaltyCardTiers {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[GetLoyaltyGroupsAndTiersDataRequest Class](getloyaltygroupsandtiersdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


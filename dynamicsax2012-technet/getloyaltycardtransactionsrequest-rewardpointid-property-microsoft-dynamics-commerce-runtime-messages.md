---
title: GetLoyaltyCardTransactionsRequest.RewardPointId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: RewardPointId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetLoyaltyCardTransactionsRequest.RewardPointId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getloyaltycardtransactionsrequest.rewardpointid(v=AX.60)
ms:contentKeyID: 62203719
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetLoyaltyCardTransactionsRequest.RewardPointId
dev_langs:
- CSharp
- C++
- VB
---

# RewardPointId Property

Gets or sets the readable identifier of the reward point.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property RewardPointId As String
    Get
    Set
'Usage
Dim instance As GetLoyaltyCardTransactionsRequest
Dim value As String

value = instance.RewardPointId

instance.RewardPointId = value
```

``` csharp
[DataMemberAttribute]
public string RewardPointId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ RewardPointId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetLoyaltyCardTransactionsRequest Class](getloyaltycardtransactionsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


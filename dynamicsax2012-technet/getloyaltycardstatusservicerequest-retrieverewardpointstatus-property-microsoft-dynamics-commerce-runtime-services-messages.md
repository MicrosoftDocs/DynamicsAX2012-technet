---
title: GetLoyaltyCardStatusServiceRequest.RetrieveRewardPointStatus Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: RetrieveRewardPointStatus Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetLoyaltyCardStatusServiceRequest.RetrieveRewardPointStatus
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getloyaltycardstatusservicerequest.retrieverewardpointstatus(v=AX.60)
ms:contentKeyID: 62204751
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetLoyaltyCardStatusServiceRequest.RetrieveRewardPointStatus
dev_langs:
- CSharp
- C++
- VB
---

# RetrieveRewardPointStatus Property

Gets or sets a value indicating whether to retrieve the reward point status of the loyalty card.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property RetrieveRewardPointStatus As Boolean
    Get
    Set
'Usage
Dim instance As GetLoyaltyCardStatusServiceRequest
Dim value As Boolean

value = instance.RetrieveRewardPointStatus

instance.RetrieveRewardPointStatus = value
```

``` csharp
[DataMemberAttribute]
public bool RetrieveRewardPointStatus { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool RetrieveRewardPointStatus {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[GetLoyaltyCardStatusServiceRequest Class](getloyaltycardstatusservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


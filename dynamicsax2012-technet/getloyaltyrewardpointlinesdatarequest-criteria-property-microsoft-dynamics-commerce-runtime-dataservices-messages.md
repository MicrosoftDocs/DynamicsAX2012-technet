---
title: GetLoyaltyRewardPointLinesDataRequest.Criteria Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: Criteria Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetLoyaltyRewardPointLinesDataRequest.Criteria
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getloyaltyrewardpointlinesdatarequest.criteria(v=AX.60)
ms:contentKeyID: 65315493
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetLoyaltyRewardPointLinesDataRequest.Criteria
dev_langs:
- CSharp
- C++
- VB
---

# Criteria Property

Gets query criteria.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property Criteria As LoyaltyRewardPointLinesQueryCriteria
    Get
    Private Set
'Usage
Dim instance As GetLoyaltyRewardPointLinesDataRequest
Dim value As LoyaltyRewardPointLinesQueryCriteria

value = instance.Criteria
```

``` csharp
public LoyaltyRewardPointLinesQueryCriteria Criteria { get; private set; }
```

``` c++
public:
property LoyaltyRewardPointLinesQueryCriteria^ Criteria {
    LoyaltyRewardPointLinesQueryCriteria^ get ();
    private: void set (LoyaltyRewardPointLinesQueryCriteria^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPointLinesQueryCriteria](loyaltyrewardpointlinesquerycriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [LoyaltyRewardPointLinesQueryCriteria](loyaltyrewardpointlinesquerycriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetLoyaltyRewardPointLinesDataRequest Class](getloyaltyrewardpointlinesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


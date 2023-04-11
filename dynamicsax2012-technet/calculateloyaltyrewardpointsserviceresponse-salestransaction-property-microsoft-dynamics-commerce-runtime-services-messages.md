---
title: CalculateLoyaltyRewardPointsServiceResponse.SalesTransaction Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: SalesTransaction Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateLoyaltyRewardPointsServiceResponse.SalesTransaction
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.calculateloyaltyrewardpointsserviceresponse.salestransaction(v=AX.60)
ms:contentKeyID: 62211937
author: tfehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateLoyaltyRewardPointsServiceResponse.SalesTransaction
dev_langs:
- CSharp
- C++
- VB
---

# SalesTransaction Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the sales transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SalesTransaction As SalesTransaction
    Get
    Private Set
'Usage
Dim instance As CalculateLoyaltyRewardPointsServiceResponse
Dim value As SalesTransaction

value = instance.SalesTransaction
```

``` csharp
[DataMemberAttribute]
public SalesTransaction SalesTransaction { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property SalesTransaction^ SalesTransaction {
    SalesTransaction^ get ();
    private: void set (SalesTransaction^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[CalculateLoyaltyRewardPointsServiceResponse Class](calculateloyaltyrewardpointsserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


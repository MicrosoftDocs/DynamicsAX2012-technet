---
title: LoyaltyCardTransaction.RewardPointAmountQuantity Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: RewardPointAmountQuantity Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyCardTransaction.RewardPointAmountQuantity
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.loyaltycardtransaction.rewardpointamountquantity(v=AX.60)
ms:contentKeyID: 62206576
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyCardTransaction.RewardPointAmountQuantity
dev_langs:
- CSharp
- C++
- VB
---

# RewardPointAmountQuantity Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the amount or the quantity of the reward point.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property RewardPointAmountQuantity As Decimal
    Get
    Friend Set
'Usage
Dim instance As LoyaltyCardTransaction
Dim value As Decimal

value = instance.RewardPointAmountQuantity
```

``` csharp
[DataMemberAttribute]
public decimal RewardPointAmountQuantity { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal RewardPointAmountQuantity {
    Decimal get ();
    internal: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltyCardTransaction Class](loyaltycardtransaction-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)


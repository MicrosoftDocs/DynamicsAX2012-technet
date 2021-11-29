---
title: LoyaltyCardTransactionsResponse.LoyaltyCardTransactions Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: LoyaltyCardTransactions Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyCardTransactionsResponse.LoyaltyCardTransactions
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.loyaltycardtransactionsresponse.loyaltycardtransactions(v=AX.60)
ms:contentKeyID: 62204885
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyCardTransactionsResponse.LoyaltyCardTransactions
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyCardTransactions Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of loyalty cards.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LoyaltyCardTransactions As ReadOnlyCollection(Of LoyaltyCardTransaction)
    Get
    Friend Set
'Usage
Dim instance As LoyaltyCardTransactionsResponse
Dim value As ReadOnlyCollection(Of LoyaltyCardTransaction)

value = instance.LoyaltyCardTransactions
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<LoyaltyCardTransaction> LoyaltyCardTransactions { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<LoyaltyCardTransaction^>^ LoyaltyCardTransactions {
    ReadOnlyCollection<LoyaltyCardTransaction^>^ get ();
    internal: void set (ReadOnlyCollection<LoyaltyCardTransaction^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[LoyaltyCardTransaction](loyaltycardtransaction-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltyCardTransactionsResponse Class](loyaltycardtransactionsresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)


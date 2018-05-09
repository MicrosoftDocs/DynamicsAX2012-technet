---
title: AffiliationLoyaltyTiersResponse.AffiliationLoyaltyTiers Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: AffiliationLoyaltyTiers Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.AffiliationLoyaltyTiersResponse.AffiliationLoyaltyTiers
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.services.affiliationloyaltytiersresponse.affiliationloyaltytiers(v=AX.60)
ms:contentKeyID: 65315719
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.AffiliationLoyaltyTiersResponse.AffiliationLoyaltyTiers
dev_langs:
- CSharp
- C++
- VB
---

# AffiliationLoyaltyTiers Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property AffiliationLoyaltyTiers As IEnumerable(Of Long)
    Get
    Set
'Usage
Dim instance As AffiliationLoyaltyTiersResponse
Dim value As IEnumerable(Of Long)

value = instance.AffiliationLoyaltyTiers

instance.AffiliationLoyaltyTiers = value
```

``` csharp
[DataMemberAttribute]
public IEnumerable<long> AffiliationLoyaltyTiers { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<long long>^ AffiliationLoyaltyTiers {
    IEnumerable<long long>^ get ();
    void set (IEnumerable<long long>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))\>  

## See Also

#### Reference

[AffiliationLoyaltyTiersResponse Class](affiliationloyaltytiersresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)


---
title: SelectedLineShippingInfo.ShipToAddress Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models)
TOCTitle: ShipToAddress Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.SelectedLineShippingInfo.ShipToAddress
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.models.selectedlineshippinginfo.shiptoaddress(v=AX.60)
ms:contentKeyID: 65318006
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.SelectedLineShippingInfo.ShipToAddress
dev_langs:
- CSharp
- C++
- VB
---

# ShipToAddress Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ShipToAddress As Address
    Get
    Set
'Usage
Dim instance As SelectedLineShippingInfo
Dim value As Address

value = instance.ShipToAddress

instance.ShipToAddress = value
```

``` csharp
[DataMemberAttribute]
public Address ShipToAddress { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Address^ ShipToAddress {
    Address^ get ();
    void set (Address^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.Address](address-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

## See Also

#### Reference

[SelectedLineShippingInfo Class](selectedlineshippinginfo-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)


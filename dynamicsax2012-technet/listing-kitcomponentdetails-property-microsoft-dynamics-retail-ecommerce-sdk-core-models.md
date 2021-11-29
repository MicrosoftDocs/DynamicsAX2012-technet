---
title: Listing.KitComponentDetails Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models)
TOCTitle: KitComponentDetails Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.Listing.KitComponentDetails
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.models.listing.kitcomponentdetails(v=AX.60)
ms:contentKeyID: 65317785
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.Listing.KitComponentDetails
dev_langs:
- CSharp
- C++
- VB
---

# KitComponentDetails Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property KitComponentDetails As Collection(Of KitComponentInfo)
    Get
    Set
'Usage
Dim instance As Listing
Dim value As Collection(Of KitComponentInfo)

value = instance.KitComponentDetails

instance.KitComponentDetails = value
```

``` csharp
[DataMemberAttribute]
public Collection<KitComponentInfo> KitComponentDetails { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<KitComponentInfo^>^ KitComponentDetails {
    Collection<KitComponentInfo^>^ get ();
    void set (Collection<KitComponentInfo^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[KitComponentInfo](kitcomponentinfo-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[Listing Class](listing-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)


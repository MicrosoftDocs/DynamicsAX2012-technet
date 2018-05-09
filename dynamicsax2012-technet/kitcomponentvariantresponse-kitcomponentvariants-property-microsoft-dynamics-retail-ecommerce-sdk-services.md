---
title: KitComponentVariantResponse.KitComponentVariants Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: KitComponentVariants Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.KitComponentVariantResponse.KitComponentVariants
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.services.kitcomponentvariantresponse.kitcomponentvariants(v=AX.60)
ms:contentKeyID: 65315657
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.KitComponentVariantResponse.KitComponentVariants
dev_langs:
- CSharp
- C++
- VB
---

# KitComponentVariants Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property KitComponentVariants As IEnumerable(Of StorefrontListItem)
    Get
    Set
'Usage
Dim instance As KitComponentVariantResponse
Dim value As IEnumerable(Of StorefrontListItem)

value = instance.KitComponentVariants

instance.KitComponentVariants = value
```

``` csharp
[DataMemberAttribute]
public IEnumerable<StorefrontListItem> KitComponentVariants { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<StorefrontListItem^>^ KitComponentVariants {
    IEnumerable<StorefrontListItem^>^ get ();
    void set (IEnumerable<StorefrontListItem^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[StorefrontListItem](storefrontlistitem-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[KitComponentVariantResponse Class](kitcomponentvariantresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)


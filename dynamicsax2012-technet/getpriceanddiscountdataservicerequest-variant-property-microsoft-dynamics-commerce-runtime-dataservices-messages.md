---
title: GetPriceAndDiscountDataServiceRequest.Variant Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: Variant Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPriceAndDiscountDataServiceRequest.Variant
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getpriceanddiscountdataservicerequest.variant(v=AX.60)
ms:contentKeyID: 65316083
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPriceAndDiscountDataServiceRequest.Variant
dev_langs:
- CSharp
- C++
- VB
---

# Variant Property

Gets or sets the product variant.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Variant As ProductVariant
    Get
    Protected Set
'Usage
Dim instance As GetPriceAndDiscountDataServiceRequest
Dim value As ProductVariant

value = instance.Variant

instance.Variant = value
```

``` csharp
[DataMemberAttribute]
public ProductVariant Variant { get; protected set; }
```

``` c++
[DataMemberAttribute]
public:
property ProductVariant^ Variant {
    ProductVariant^ get ();
    protected: void set (ProductVariant^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant](productvariant-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ProductVariant](productvariant-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetPriceAndDiscountDataServiceRequest Class](getpriceanddiscountdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


---
title: GetPriceAndDiscountDataServiceRequest.PriceDiscountType Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: PriceDiscountType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPriceAndDiscountDataServiceRequest.PriceDiscountType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getpriceanddiscountdataservicerequest.pricediscounttype(v=AX.60)
ms:contentKeyID: 65318727
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPriceAndDiscountDataServiceRequest.PriceDiscountType
dev_langs:
- CSharp
- C++
- VB
---

# PriceDiscountType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the product discount type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PriceDiscountType As PriceDiscountType
    Get
    Protected Set
'Usage
Dim instance As GetPriceAndDiscountDataServiceRequest
Dim value As PriceDiscountType

value = instance.PriceDiscountType

instance.PriceDiscountType = value
```

``` csharp
[DataMemberAttribute]
public PriceDiscountType PriceDiscountType { get; protected set; }
```

``` c++
[DataMemberAttribute]
public:
property PriceDiscountType PriceDiscountType {
    PriceDiscountType get ();
    protected: void set (PriceDiscountType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceDiscountType](pricediscounttype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [PriceDiscountType](pricediscounttype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetPriceAndDiscountDataServiceRequest Class](getpriceanddiscountdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


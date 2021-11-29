---
title: GetPriceAndDiscountDataServiceRequest.ItemCode Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: ItemCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPriceAndDiscountDataServiceRequest.ItemCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getpriceanddiscountdataservicerequest.itemcode(v=AX.60)
ms:contentKeyID: 65321566
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPriceAndDiscountDataServiceRequest.ItemCode
dev_langs:
- CSharp
- C++
- VB
---

# ItemCode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the discount item code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ItemCode As PriceDiscountItemCode
    Get
    Protected Set
'Usage
Dim instance As GetPriceAndDiscountDataServiceRequest
Dim value As PriceDiscountItemCode

value = instance.ItemCode

instance.ItemCode = value
```

``` csharp
[DataMemberAttribute]
public PriceDiscountItemCode ItemCode { get; protected set; }
```

``` c++
[DataMemberAttribute]
public:
property PriceDiscountItemCode ItemCode {
    PriceDiscountItemCode get ();
    protected: void set (PriceDiscountItemCode value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceDiscountItemCode](pricediscountitemcode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [PriceDiscountItemCode](pricediscountitemcode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetPriceAndDiscountDataServiceRequest Class](getpriceanddiscountdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


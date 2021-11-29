---
title: GetPriceAndDiscountDataServiceRequest.AccountCode Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: AccountCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPriceAndDiscountDataServiceRequest.AccountCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getpriceanddiscountdataservicerequest.accountcode(v=AX.60)
ms:contentKeyID: 65317550
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPriceAndDiscountDataServiceRequest.AccountCode
dev_langs:
- CSharp
- C++
- VB
---

# AccountCode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the discount account code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property AccountCode As PriceDiscountAccountCode
    Get
    Protected Set
'Usage
Dim instance As GetPriceAndDiscountDataServiceRequest
Dim value As PriceDiscountAccountCode

value = instance.AccountCode

instance.AccountCode = value
```

``` csharp
[DataMemberAttribute]
public PriceDiscountAccountCode AccountCode { get; protected set; }
```

``` c++
[DataMemberAttribute]
public:
property PriceDiscountAccountCode AccountCode {
    PriceDiscountAccountCode get ();
    protected: void set (PriceDiscountAccountCode value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceDiscountAccountCode](pricediscountaccountcode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [PriceDiscountAccountCode](pricediscountaccountcode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetPriceAndDiscountDataServiceRequest Class](getpriceanddiscountdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


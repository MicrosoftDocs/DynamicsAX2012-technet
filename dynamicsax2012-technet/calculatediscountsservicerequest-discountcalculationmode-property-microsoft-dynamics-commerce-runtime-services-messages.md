---
title: CalculateDiscountsServiceRequest.DiscountCalculationMode Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: DiscountCalculationMode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateDiscountsServiceRequest.DiscountCalculationMode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.calculatediscountsservicerequest.discountcalculationmode(v=AX.60)
ms:contentKeyID: 62211687
author: tfehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateDiscountsServiceRequest.DiscountCalculationMode
dev_langs:
- CSharp
- C++
- VB
---

# DiscountCalculationMode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the discount calculation mode.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<RequiredAttribute> _
Public Property DiscountCalculationMode As DiscountCalculationMode
    Get
    Private Set
'Usage
Dim instance As CalculateDiscountsServiceRequest
Dim value As DiscountCalculationMode

value = instance.DiscountCalculationMode
```

``` csharp
[DataMemberAttribute]
[RequiredAttribute]
public DiscountCalculationMode DiscountCalculationMode { get; private set; }
```

``` c++
[DataMemberAttribute]
[RequiredAttribute]
public:
property DiscountCalculationMode DiscountCalculationMode {
    DiscountCalculationMode get ();
    private: void set (DiscountCalculationMode value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountCalculationMode](discountcalculationmode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [DiscountCalculationMode](discountcalculationmode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[CalculateDiscountsServiceRequest Class](calculatediscountsservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


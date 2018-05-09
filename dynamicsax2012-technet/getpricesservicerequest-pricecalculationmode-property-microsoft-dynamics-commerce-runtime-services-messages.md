---
title: GetPricesServiceRequest.PriceCalculationMode Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: PriceCalculationMode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetPricesServiceRequest.PriceCalculationMode
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getpricesservicerequest.pricecalculationmode(v=AX.60)
ms:contentKeyID: 62211918
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetPricesServiceRequest.PriceCalculationMode
dev_langs:
- CSharp
- C++
- VB
---

# PriceCalculationMode Property

Gets the price calculation mode for the lines being calculated.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<RequiredAttribute> _
<DataMemberAttribute> _
Public Property PriceCalculationMode As PricingCalculationMode
    Get
    Private Set
'Usage
Dim instance As GetPricesServiceRequest
Dim value As PricingCalculationMode

value = instance.PriceCalculationMode
```

``` csharp
[RequiredAttribute]
[DataMemberAttribute]
public PricingCalculationMode PriceCalculationMode { get; private set; }
```

``` c++
[RequiredAttribute]
[DataMemberAttribute]
public:
property PricingCalculationMode PriceCalculationMode {
    PricingCalculationMode get ();
    private: void set (PricingCalculationMode value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PricingCalculationMode](pricingcalculationmode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [PricingCalculationMode](pricingcalculationmode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetPricesServiceRequest Class](getpricesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


---
title: GetPriceAndDiscountDataServiceRequest Class (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetPriceAndDiscountDataServiceRequest Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPriceAndDiscountDataServiceRequest
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getpriceanddiscountdataservicerequest(v=AX.60)
ms:contentKeyID: 65320977
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPriceAndDiscountDataServiceRequest
dev_langs:
- CSharp
- C++
- VB
---

# GetPriceAndDiscountDataServiceRequest Class

The data service request to get the price and discount values.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public MustInherit Class GetPriceAndDiscountDataServiceRequest _
    Inherits DataRequest
'Usage
Dim instance As GetPriceAndDiscountDataServiceRequest
```

``` csharp
[DataContractAttribute]
public abstract class GetPriceAndDiscountDataServiceRequest : DataRequest
```

``` c++
[DataContractAttribute]
public ref class GetPriceAndDiscountDataServiceRequest abstract : public DataRequest
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Messages.Request](request-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.DataRequest](datarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPriceAndDiscountDataServiceRequest  
        [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.FindPriceAdjustmentsDataServiceRequest](findpriceadjustmentsdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
        [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.FindTradeAgreementsDataServiceRequest](findtradeagreementsdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
        [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetDiscountCodesDataServiceRequest](getdiscountcodesdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
        [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPeriodicDiscountsDataServiceRequest](getperiodicdiscountsdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
        [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ReadDiscountTradeAgreementsDataServiceRequest](readdiscounttradeagreementsdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
        [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ReadPriceAdjustmentsDataServiceRequest](readpriceadjustmentsdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
        [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ReadPriceTradeAgreementsDataServiceRequest](readpricetradeagreementsdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
        [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ReadRetailDiscountsDataServiceRequest](readretaildiscountsdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


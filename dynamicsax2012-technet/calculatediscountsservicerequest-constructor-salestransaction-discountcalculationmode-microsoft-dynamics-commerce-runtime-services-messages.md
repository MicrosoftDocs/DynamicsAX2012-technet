---
title: CalculateDiscountsServiceRequest Constructor (SalesTransaction, DiscountCalculationMode) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: CalculateDiscountsServiceRequest Constructor (SalesTransaction, DiscountCalculationMode)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateDiscountsServiceRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction,Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountCalculationMode)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.calculatediscountsservicerequest.calculatediscountsservicerequest(v=AX.60)
ms:contentKeyID: 65318938
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CalculateDiscountsServiceRequest Constructor (SalesTransaction, DiscountCalculationMode)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    transaction As SalesTransaction, _
    discountCalculationMode As DiscountCalculationMode _
)
'Usage
Dim transaction As SalesTransaction
Dim discountCalculationMode As DiscountCalculationMode

Dim instance As New CalculateDiscountsServiceRequest(transaction, _
    discountCalculationMode)
```

``` csharp
public CalculateDiscountsServiceRequest(
    SalesTransaction transaction,
    DiscountCalculationMode discountCalculationMode
)
```

``` c++
public:
CalculateDiscountsServiceRequest(
    SalesTransaction^ transaction, 
    DiscountCalculationMode discountCalculationMode
)
```

#### Parameters

  - transaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - discountCalculationMode  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountCalculationMode](discountcalculationmode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[CalculateDiscountsServiceRequest Class](calculatediscountsservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[CalculateDiscountsServiceRequest Overload](calculatediscountsservicerequest-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


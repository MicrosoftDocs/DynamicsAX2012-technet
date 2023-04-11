---
title: GetCustomerOrderCalculationModesServiceResponse.CalculationModes Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: CalculationModes Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCustomerOrderCalculationModesServiceResponse.CalculationModes
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getcustomerordercalculationmodesserviceresponse.calculationmodes(v=AX.60)
ms:contentKeyID: 62209340
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCustomerOrderCalculationModesServiceResponse.CalculationModes
dev_langs:
- CSharp
- C++
- VB
---

# CalculationModes Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the calculation modes.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CalculationModes As CalculationModes
    Get
    Private Set
'Usage
Dim instance As GetCustomerOrderCalculationModesServiceResponse
Dim value As CalculationModes

value = instance.CalculationModes
```

``` csharp
[DataMemberAttribute]
public CalculationModes CalculationModes { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property CalculationModes CalculationModes {
    CalculationModes get ();
    private: void set (CalculationModes value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CalculationModes](calculationmodes-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [CalculationModes](calculationmodes-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetCustomerOrderCalculationModesServiceResponse Class](getcustomerordercalculationmodesserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


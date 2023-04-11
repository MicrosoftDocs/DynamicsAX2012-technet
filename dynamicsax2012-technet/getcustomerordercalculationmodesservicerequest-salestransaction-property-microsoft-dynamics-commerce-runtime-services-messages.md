---
title: GetCustomerOrderCalculationModesServiceRequest.SalesTransaction Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: SalesTransaction Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCustomerOrderCalculationModesServiceRequest.SalesTransaction
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getcustomerordercalculationmodesservicerequest.salestransaction(v=AX.60)
ms:contentKeyID: 62205121
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCustomerOrderCalculationModesServiceRequest.SalesTransaction
dev_langs:
- CSharp
- C++
- VB
---

# SalesTransaction Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the sales transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<RequiredAttribute> _
Public Property SalesTransaction As SalesTransaction
    Get
    Set
'Usage
Dim instance As GetCustomerOrderCalculationModesServiceRequest
Dim value As SalesTransaction

value = instance.SalesTransaction

instance.SalesTransaction = value
```

``` csharp
[DataMemberAttribute]
[RequiredAttribute]
public SalesTransaction SalesTransaction { get; set; }
```

``` c++
[DataMemberAttribute]
[RequiredAttribute]
public:
property SalesTransaction^ SalesTransaction {
    SalesTransaction^ get ();
    void set (SalesTransaction^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetCustomerOrderCalculationModesServiceRequest Class](getcustomerordercalculationmodesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


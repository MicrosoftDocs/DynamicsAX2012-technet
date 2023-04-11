---
title: GetAllPeriodicDiscountsServiceRequest.Transaction Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Transaction Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetAllPeriodicDiscountsServiceRequest.Transaction
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getallperiodicdiscountsservicerequest.transaction(v=AX.60)
ms:contentKeyID: 62213552
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetAllPeriodicDiscountsServiceRequest.Transaction
dev_langs:
- CSharp
- C++
- VB
---

# Transaction Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the transaction for which the discounts need to be read.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<RequiredAttribute> _
<DataMemberAttribute> _
Public Property Transaction As SalesTransaction
    Get
    Private Set
'Usage
Dim instance As GetAllPeriodicDiscountsServiceRequest
Dim value As SalesTransaction

value = instance.Transaction
```

``` csharp
[RequiredAttribute]
[DataMemberAttribute]
public SalesTransaction Transaction { get; private set; }
```

``` c++
[RequiredAttribute]
[DataMemberAttribute]
public:
property SalesTransaction^ Transaction {
    SalesTransaction^ get ();
    private: void set (SalesTransaction^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetAllPeriodicDiscountsServiceRequest Class](getallperiodicdiscountsservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


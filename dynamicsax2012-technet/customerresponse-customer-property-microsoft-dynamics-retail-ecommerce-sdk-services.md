---
title: CustomerResponse.Customer Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: Customer Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.CustomerResponse.Customer
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.customerresponse.customer(v=AX.60)
ms:contentKeyID: 65317770
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.CustomerResponse.Customer
dev_langs:
- CSharp
- C++
- VB
---

# Customer Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Customer As Customer
    Get
    Set
'Usage
Dim instance As CustomerResponse
Dim value As Customer

value = instance.Customer

instance.Customer = value
```

``` csharp
[DataMemberAttribute]
public Customer Customer { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Customer^ Customer {
    Customer^ get ();
    void set (Customer^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.Customer](customer-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

## See Also

#### Reference

[CustomerResponse Class](customerresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)


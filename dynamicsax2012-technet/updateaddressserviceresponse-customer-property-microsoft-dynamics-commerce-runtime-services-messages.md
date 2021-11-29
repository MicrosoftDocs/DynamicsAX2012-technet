---
title: UpdateAddressServiceResponse.Customer Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Customer Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UpdateAddressServiceResponse.Customer
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.updateaddressserviceresponse.customer(v=AX.60)
ms:contentKeyID: 65317581
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UpdateAddressServiceResponse.Customer
dev_langs:
- CSharp
- C++
- VB
---

# Customer Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Customer As Customer
    Get
    Private Set
'Usage
Dim instance As UpdateAddressServiceResponse
Dim value As Customer

value = instance.Customer
```

``` csharp
[DataMemberAttribute]
public Customer Customer { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Customer^ Customer {
    Customer^ get ();
    private: void set (Customer^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[UpdateAddressServiceResponse Class](updateaddressserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


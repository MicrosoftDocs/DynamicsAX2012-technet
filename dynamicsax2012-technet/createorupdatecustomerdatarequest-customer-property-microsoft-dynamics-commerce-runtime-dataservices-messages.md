---
title: CreateOrUpdateCustomerDataRequest.Customer Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: Customer Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.CreateOrUpdateCustomerDataRequest.Customer
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.createorupdatecustomerdatarequest.customer(v=AX.60)
ms:contentKeyID: 65318847
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.CreateOrUpdateCustomerDataRequest.Customer
dev_langs:
- CSharp
- C++
- VB
---

# Customer Property

Gets the customer to be created or updated.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Customer As Customer
    Get
    Private Set
'Usage
Dim instance As CreateOrUpdateCustomerDataRequest
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
The customer instance to be created or updated  

## See Also

#### Reference

[CreateOrUpdateCustomerDataRequest Class](createorupdatecustomerdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


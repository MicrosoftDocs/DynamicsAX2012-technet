---
title: CreateCustomerResponse.CreatedCustomer Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: CreatedCustomer Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.CreateCustomerResponse.CreatedCustomer
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.createcustomerresponse.createdcustomer(v=AX.60)
ms:contentKeyID: 49839963
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.CreateCustomerResponse.CreatedCustomer
dev_langs:
- CSharp
- C++
- VB
---

# CreatedCustomer Property

Gets the created customer.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CreatedCustomer As Customer
    Get
    Private Set
'Usage
Dim instance As CreateCustomerResponse
Dim value As Customer

value = instance.CreatedCustomer
```

``` csharp
[DataMemberAttribute]
public Customer CreatedCustomer { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Customer^ CreatedCustomer {
    Customer^ get ();
    private: void set (Customer^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [Customer](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[CreateCustomerResponse Class](createcustomerresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


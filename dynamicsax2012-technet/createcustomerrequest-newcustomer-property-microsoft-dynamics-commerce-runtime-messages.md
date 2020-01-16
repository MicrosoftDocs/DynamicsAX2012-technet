---
title: CreateCustomerRequest.NewCustomer Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: NewCustomer Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.CreateCustomerRequest.NewCustomer
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.createcustomerrequest.newcustomer(v=AX.60)
ms:contentKeyID: 49851985
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.CreateCustomerRequest.NewCustomer
dev_langs:
- CSharp
- C++
- VB
---

# NewCustomer Property

Gets or sets the customer to create.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property NewCustomer As Customer
    Get
    Set
'Usage
Dim instance As CreateCustomerRequest
Dim value As Customer

value = instance.NewCustomer

instance.NewCustomer = value
```

``` csharp
[DataMemberAttribute]
public Customer NewCustomer { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Customer^ NewCustomer {
    Customer^ get ();
    void set (Customer^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [Customer](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[CreateCustomerRequest Class](createcustomerrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


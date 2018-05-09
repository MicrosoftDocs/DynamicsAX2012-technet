---
title: UpdateCustomerRequest.UpdatedCustomer Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: UpdatedCustomer Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.UpdateCustomerRequest.UpdatedCustomer
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.updatecustomerrequest.updatedcustomer(v=AX.60)
ms:contentKeyID: 49851712
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.UpdateCustomerRequest.UpdatedCustomer
dev_langs:
- CSharp
- C++
- VB
---

# UpdatedCustomer Property

Gets or sets the customer to update.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property UpdatedCustomer As Customer
    Get
    Set
'Usage
Dim instance As UpdateCustomerRequest
Dim value As Customer

value = instance.UpdatedCustomer

instance.UpdatedCustomer = value
```

``` csharp
[DataMemberAttribute]
public Customer UpdatedCustomer { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Customer^ UpdatedCustomer {
    Customer^ get ();
    void set (Customer^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [Customer](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[UpdateCustomerRequest Class](updatecustomerrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


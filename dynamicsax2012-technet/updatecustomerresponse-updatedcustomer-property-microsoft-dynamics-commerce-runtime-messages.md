---
title: UpdateCustomerResponse.UpdatedCustomer Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: UpdatedCustomer Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.UpdateCustomerResponse.UpdatedCustomer
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.updatecustomerresponse.updatedcustomer(v=AX.60)
ms:contentKeyID: 49854397
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.UpdateCustomerResponse.UpdatedCustomer
dev_langs:
- CSharp
- C++
- VB
---

# UpdatedCustomer Property

Gets the updated customer.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property UpdatedCustomer As Customer
    Get
    Private Set
'Usage
Dim instance As UpdateCustomerResponse
Dim value As Customer

value = instance.UpdatedCustomer
```

``` csharp
[DataMemberAttribute]
public Customer UpdatedCustomer { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Customer^ UpdatedCustomer {
    Customer^ get ();
    private: void set (Customer^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [Customer](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[UpdateCustomerResponse Class](updatecustomerresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


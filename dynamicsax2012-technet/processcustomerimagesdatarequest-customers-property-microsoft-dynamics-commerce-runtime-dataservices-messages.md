---
title: ProcessCustomerImagesDataRequest.Customers Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: Customers Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ProcessCustomerImagesDataRequest.Customers
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.processcustomerimagesdatarequest.customers(v=AX.60)
ms:contentKeyID: 65317233
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ProcessCustomerImagesDataRequest.Customers
dev_langs:
- CSharp
- C++
- VB
---

# Customers Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the customers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Customers As ICollection(Of Customer)
    Get
    Private Set
'Usage
Dim instance As ProcessCustomerImagesDataRequest
Dim value As ICollection(Of Customer)

value = instance.Customers
```

``` csharp
[DataMemberAttribute]
public ICollection<Customer> Customers { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<Customer^>^ Customers {
    ICollection<Customer^>^ get ();
    private: void set (ICollection<Customer^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[Customer](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The customers.  

## See Also

#### Reference

[ProcessCustomerImagesDataRequest Class](processcustomerimagesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


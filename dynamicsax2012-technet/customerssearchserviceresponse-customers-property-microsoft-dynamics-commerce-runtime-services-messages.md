---
title: CustomersSearchServiceResponse.Customers Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Customers Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CustomersSearchServiceResponse.Customers
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.customerssearchserviceresponse.customers(v=AX.60)
ms:contentKeyID: 62206447
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CustomersSearchServiceResponse.Customers
dev_langs:
- CSharp
- C++
- VB
---

# Customers Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of customers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Customers As ReadOnlyCollection(Of GlobalCustomer)
    Get
    Private Set
'Usage
Dim instance As CustomersSearchServiceResponse
Dim value As ReadOnlyCollection(Of GlobalCustomer)

value = instance.Customers
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<GlobalCustomer> Customers { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<GlobalCustomer^>^ Customers {
    ReadOnlyCollection<GlobalCustomer^>^ get ();
    private: void set (ReadOnlyCollection<GlobalCustomer^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[GlobalCustomer](globalcustomer-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[CustomersSearchServiceResponse Class](customerssearchserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


---
title: CustomersSearchResponse.Customers Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Customers Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.CustomersSearchResponse.Customers
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.customerssearchresponse.customers(v=AX.60)
ms:contentKeyID: 62208364
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.CustomersSearchResponse.Customers
dev_langs:
- CSharp
- C++
- VB
---

# Customers Property

Gets the collection of customers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Customers As ReadOnlyCollection(Of GlobalCustomer)
    Get
    Private Set
'Usage
Dim instance As CustomersSearchResponse
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

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[GlobalCustomer](globalcustomer-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[CustomersSearchResponse Class](customerssearchresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


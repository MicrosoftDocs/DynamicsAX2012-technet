---
title: GetCustomersResponse.Customers Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Customers Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetCustomersResponse.Customers
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getcustomersresponse.customers(v=AX.60)
ms:contentKeyID: 49836731
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetCustomersResponse.Customers
dev_langs:
- CSharp
- C++
- VB
---

# Customers Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of customers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Customers As ReadOnlyCollection(Of Customer)
    Get
    Private Set
'Usage
Dim instance As GetCustomersResponse
Dim value As ReadOnlyCollection(Of Customer)

value = instance.Customers
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<Customer> Customers { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<Customer^>^ Customers {
    ReadOnlyCollection<Customer^>^ get ();
    private: void set (ReadOnlyCollection<Customer^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Customer](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetCustomersResponse Class](getcustomersresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


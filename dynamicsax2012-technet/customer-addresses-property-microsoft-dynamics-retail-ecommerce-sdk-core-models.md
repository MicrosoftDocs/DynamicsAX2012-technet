---
title: Customer.Addresses Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models)
TOCTitle: Addresses Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.Customer.Addresses
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.models.customer.addresses(v=AX.60)
ms:contentKeyID: 65317679
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.Customer.Addresses
dev_langs:
- CSharp
- C++
- VB
---

# Addresses Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Addresses As IEnumerable(Of Address)
    Get
    Set
'Usage
Dim instance As Customer
Dim value As IEnumerable(Of Address)

value = instance.Addresses

instance.Addresses = value
```

``` csharp
[DataMemberAttribute]
public IEnumerable<Address> Addresses { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<Address^>^ Addresses {
    IEnumerable<Address^>^ get ();
    void set (IEnumerable<Address^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Address](address-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)


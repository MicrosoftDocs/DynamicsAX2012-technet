---
title: Customer.NewCustomerPartyNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: NewCustomerPartyNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.NewCustomerPartyNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customer.newcustomerpartynumber(v=AX.60)
ms:contentKeyID: 62208279
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.NewCustomerPartyNumber
dev_langs:
- CSharp
- C++
- VB
---

# NewCustomerPartyNumber Property

Gets or sets the new customer party number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property NewCustomerPartyNumber As String
    Get
    Set
'Usage
Dim instance As Customer
Dim value As String

value = instance.NewCustomerPartyNumber

instance.NewCustomerPartyNumber = value
```

``` csharp
[DataMemberAttribute]
public string NewCustomerPartyNumber { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ NewCustomerPartyNumber {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The new customer party number.  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


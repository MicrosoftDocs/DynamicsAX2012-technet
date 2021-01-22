---
title: Customer.CNPJCPFNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CNPJCPFNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.CNPJCPFNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customer.cnpjcpfnumber(v=AX.60)
ms:contentKeyID: 62210728
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.CNPJCPFNumber
dev_langs:
- CSharp
- C++
- VB
---

# CNPJCPFNumber Property

Gets or sets the value for CNPJCPFNumber.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CNPJCPFNUMBER")> _
<DataMemberAttribute> _
Public Property CNPJCPFNumber As String
    Get
    Set
'Usage
Dim instance As Customer
Dim value As String

value = instance.CNPJCPFNumber

instance.CNPJCPFNumber = value
```

``` csharp
[ColumnAttribute("CNPJCPFNUMBER")]
[DataMemberAttribute]
public string CNPJCPFNumber { get; set; }
```

``` c++
[ColumnAttribute(L"CNPJCPFNUMBER")]
[DataMemberAttribute]
public:
property String^ CNPJCPFNumber {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


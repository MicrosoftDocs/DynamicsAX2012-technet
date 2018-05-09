---
title: Customer.AccountNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AccountNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.AccountNumber
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.customer.accountnumber(v=AX.60)
ms:contentKeyID: 49829720
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.AccountNumber
dev_langs:
- CSharp
- C++
- VB
---

# AccountNumber Property

Gets or sets the account number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ACCOUNTNUMBER")> _
<DataMemberAttribute> _
<KeyAttribute> _
Public Property AccountNumber As String
    Get
    Set
'Usage
Dim instance As Customer
Dim value As String

value = instance.AccountNumber

instance.AccountNumber = value
```

``` csharp
[ColumnAttribute("ACCOUNTNUMBER")]
[DataMemberAttribute]
[KeyAttribute]
public string AccountNumber { get; set; }
```

``` c++
[ColumnAttribute(L"ACCOUNTNUMBER")]
[DataMemberAttribute]
[KeyAttribute]
public:
property String^ AccountNumber {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The account number.  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


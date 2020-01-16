---
title: Customer.MandatoryCreditLimit Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MandatoryCreditLimit Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.MandatoryCreditLimit
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customer.mandatorycreditlimit(v=AX.60)
ms:contentKeyID: 62207803
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.MandatoryCreditLimit
dev_langs:
- CSharp
- C++
- VB
---

# MandatoryCreditLimit Property

Gets or sets a value indicating whether a mandatory credit limit exists.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("MANDATORYCREDITLIMIT")> _
<DataMemberAttribute> _
Public Property MandatoryCreditLimit As Boolean
    Get
    Set
'Usage
Dim instance As Customer
Dim value As Boolean

value = instance.MandatoryCreditLimit

instance.MandatoryCreditLimit = value
```

``` csharp
[ColumnAttribute("MANDATORYCREDITLIMIT")]
[DataMemberAttribute]
public bool MandatoryCreditLimit { get; set; }
```

``` c++
[ColumnAttribute(L"MANDATORYCREDITLIMIT")]
[DataMemberAttribute]
public:
property bool MandatoryCreditLimit {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
If true a mandatory credit limit has been set; otherwise, false.  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


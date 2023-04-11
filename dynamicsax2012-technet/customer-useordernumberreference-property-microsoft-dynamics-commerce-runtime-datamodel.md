---
title: Customer.UseOrderNumberReference Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: UseOrderNumberReference Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.UseOrderNumberReference
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customer.useordernumberreference(v=AX.60)
ms:contentKeyID: 62212072
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.UseOrderNumberReference
dev_langs:
- CSharp
- C++
- VB
---

# UseOrderNumberReference Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether order number reference should be used.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("USEORDERNUMBERREFERENCE")> _
<DataMemberAttribute> _
Public Property UseOrderNumberReference As Boolean
    Get
    Set
'Usage
Dim instance As Customer
Dim value As Boolean

value = instance.UseOrderNumberReference

instance.UseOrderNumberReference = value
```

``` csharp
[ColumnAttribute("USEORDERNUMBERREFERENCE")]
[DataMemberAttribute]
public bool UseOrderNumberReference { get; set; }
```

``` c++
[ColumnAttribute(L"USEORDERNUMBERREFERENCE")]
[DataMemberAttribute]
public:
property bool UseOrderNumberReference {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
If true use order number reference; otherwise, false.  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


---
title: Customer.CellphoneRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CellphoneRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.CellphoneRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customer.cellphonerecordid(v=AX.60)
ms:contentKeyID: 62203794
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.CellphoneRecordId
dev_langs:
- CSharp
- C++
- VB
---

# CellphoneRecordId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the cellphone record id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CELLPHONERECORDID")> _
<IgnoreDataMemberAttribute> _
Public Property CellphoneRecordId As Long
    Get
    Set
'Usage
Dim instance As Customer
Dim value As Long

value = instance.CellphoneRecordId

instance.CellphoneRecordId = value
```

``` csharp
[ColumnAttribute("CELLPHONERECORDID")]
[IgnoreDataMemberAttribute]
public long CellphoneRecordId { get; set; }
```

``` c++
[ColumnAttribute(L"CELLPHONERECORDID")]
[IgnoreDataMemberAttribute]
public:
property long long CellphoneRecordId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The cellphone record id.  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


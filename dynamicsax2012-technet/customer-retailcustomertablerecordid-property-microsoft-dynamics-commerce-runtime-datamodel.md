---
title: Customer.RetailCustomerTableRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RetailCustomerTableRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.RetailCustomerTableRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customer.retailcustomertablerecordid(v=AX.60)
ms:contentKeyID: 62214640
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.RetailCustomerTableRecordId
dev_langs:
- CSharp
- C++
- VB
---

# RetailCustomerTableRecordId Property

Gets or sets the retail customer table record id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("RETAILCUSTTABLERECID")> _
Public Property RetailCustomerTableRecordId As Long
    Get
    Set
'Usage
Dim instance As Customer
Dim value As Long

value = instance.RetailCustomerTableRecordId

instance.RetailCustomerTableRecordId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("RETAILCUSTTABLERECID")]
public long RetailCustomerTableRecordId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"RETAILCUSTTABLERECID")]
public:
property long long RetailCustomerTableRecordId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The retail customer table record id.  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


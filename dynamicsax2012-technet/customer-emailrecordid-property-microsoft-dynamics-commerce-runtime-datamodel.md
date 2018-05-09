---
title: Customer.EmailRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EmailRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.EmailRecordId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.customer.emailrecordid(v=AX.60)
ms:contentKeyID: 49839161
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.EmailRecordId
dev_langs:
- CSharp
- C++
- VB
---

# EmailRecordId Property

Gets or sets the Email record identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("EMAILRECORDID")> _
Public Property EmailRecordId As Long
    Get
    Set
'Usage
Dim instance As Customer
Dim value As Long

value = instance.EmailRecordId

instance.EmailRecordId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("EMAILRECORDID")]
public long EmailRecordId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"EMAILRECORDID")]
public:
property long long EmailRecordId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  
The record identifier.  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


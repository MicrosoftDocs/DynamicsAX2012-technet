---
title: Customer.PhoneRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PhoneRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.PhoneRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customer.phonerecordid(v=AX.60)
ms:contentKeyID: 49838291
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.PhoneRecordId
dev_langs:
- CSharp
- C++
- VB
---

# PhoneRecordId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the telephone record identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PHONERECORDID")> _
<DataMemberAttribute> _
Public Property PhoneRecordId As Long
    Get
    Set
'Usage
Dim instance As Customer
Dim value As Long

value = instance.PhoneRecordId

instance.PhoneRecordId = value
```

``` csharp
[ColumnAttribute("PHONERECORDID")]
[DataMemberAttribute]
public long PhoneRecordId { get; set; }
```

``` c++
[ColumnAttribute(L"PHONERECORDID")]
[DataMemberAttribute]
public:
property long long PhoneRecordId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The record identifier.  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


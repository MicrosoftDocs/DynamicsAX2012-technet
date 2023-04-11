---
title: Customer.PhoneLogisticsLocationRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PhoneLogisticsLocationRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.PhoneLogisticsLocationRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customer.phonelogisticslocationrecordid(v=AX.60)
ms:contentKeyID: 62206533
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.PhoneLogisticsLocationRecordId
dev_langs:
- CSharp
- C++
- VB
---

# PhoneLogisticsLocationRecordId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the phone logistics location record id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("PHONELOCATIONRECORDID")> _
Public Property PhoneLogisticsLocationRecordId As Long
    Get
    Set
'Usage
Dim instance As Customer
Dim value As Long

value = instance.PhoneLogisticsLocationRecordId

instance.PhoneLogisticsLocationRecordId = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("PHONELOCATIONRECORDID")]
public long PhoneLogisticsLocationRecordId { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"PHONELOCATIONRECORDID")]
public:
property long long PhoneLogisticsLocationRecordId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The phone logistics location record id.  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


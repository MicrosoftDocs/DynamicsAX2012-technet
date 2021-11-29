---
title: Customer.CellphoneLogisticsLocationRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CellphoneLogisticsLocationRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.CellphoneLogisticsLocationRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customer.cellphonelogisticslocationrecordid(v=AX.60)
ms:contentKeyID: 62208368
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.CellphoneLogisticsLocationRecordId
dev_langs:
- CSharp
- C++
- VB
---

# CellphoneLogisticsLocationRecordId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the cellphone logistics location record id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("CELLPHONELOCATIONRECORDID")> _
Public Property CellphoneLogisticsLocationRecordId As Long
    Get
    Set
'Usage
Dim instance As Customer
Dim value As Long

value = instance.CellphoneLogisticsLocationRecordId

instance.CellphoneLogisticsLocationRecordId = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("CELLPHONELOCATIONRECORDID")]
public long CellphoneLogisticsLocationRecordId { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"CELLPHONELOCATIONRECORDID")]
public:
property long long CellphoneLogisticsLocationRecordId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The cellphone logistics location record id.  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


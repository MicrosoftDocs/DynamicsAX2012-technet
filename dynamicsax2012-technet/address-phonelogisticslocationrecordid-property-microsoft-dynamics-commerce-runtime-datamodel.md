---
title: Address.PhoneLogisticsLocationRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PhoneLogisticsLocationRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.PhoneLogisticsLocationRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.address.phonelogisticslocationrecordid(v=AX.60)
ms:contentKeyID: 62202364
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.PhoneLogisticsLocationRecordId
dev_langs:
- CSharp
- C++
- VB
---

# PhoneLogisticsLocationRecordId Property

Gets or sets the phone logistics location record id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ReadOnlyAttribute("PHONELOCATIONRECORDID")> _
<DataMemberAttribute> _
<ColumnAttribute("PHONELOCATIONRECORDID")> _
Public Property PhoneLogisticsLocationRecordId As Long
    Get
    Set
'Usage
Dim instance As Address
Dim value As Long

value = instance.PhoneLogisticsLocationRecordId

instance.PhoneLogisticsLocationRecordId = value
```

``` csharp
[ReadOnlyAttribute("PHONELOCATIONRECORDID")]
[DataMemberAttribute]
[ColumnAttribute("PHONELOCATIONRECORDID")]
public long PhoneLogisticsLocationRecordId { get; set; }
```

``` c++
[ReadOnlyAttribute(L"PHONELOCATIONRECORDID")]
[DataMemberAttribute]
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

[Address Class](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


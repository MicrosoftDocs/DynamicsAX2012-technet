---
title: Address.LogisticsLocationRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LogisticsLocationRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.LogisticsLocationRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.address.logisticslocationrecordid(v=AX.60)
ms:contentKeyID: 62202709
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.LogisticsLocationRecordId
dev_langs:
- CSharp
- C++
- VB
---

# LogisticsLocationRecordId Property

Gets or sets the logistics location record identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ReadOnlyAttribute("LOGISTICSLOCATIONRECID")> _
<ColumnAttribute("LOGISTICSLOCATIONRECID")> _
<DataMemberAttribute> _
Public Property LogisticsLocationRecordId As Long
    Get
    Set
'Usage
Dim instance As Address
Dim value As Long

value = instance.LogisticsLocationRecordId

instance.LogisticsLocationRecordId = value
```

``` csharp
[ReadOnlyAttribute("LOGISTICSLOCATIONRECID")]
[ColumnAttribute("LOGISTICSLOCATIONRECID")]
[DataMemberAttribute]
public long LogisticsLocationRecordId { get; set; }
```

``` c++
[ReadOnlyAttribute(L"LOGISTICSLOCATIONRECID")]
[ColumnAttribute(L"LOGISTICSLOCATIONRECID")]
[DataMemberAttribute]
public:
property long long LogisticsLocationRecordId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The logistics location record identifier.  

## See Also

#### Reference

[Address Class](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


---
title: Address.LogisticsLocationExtRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LogisticsLocationExtRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.LogisticsLocationExtRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.address.logisticslocationextrecordid(v=AX.60)
ms:contentKeyID: 62209213
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.LogisticsLocationExtRecordId
dev_langs:
- CSharp
- C++
- VB
---

# LogisticsLocationExtRecordId Property

Gets or sets the logistics locationExt record identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ReadOnlyAttribute("LOGISTICSLOCATIONEXTRECID")> _
<DataMemberAttribute> _
<ColumnAttribute("LOGISTICSLOCATIONEXTRECID")> _
Public Property LogisticsLocationExtRecordId As Long
    Get
    Set
'Usage
Dim instance As Address
Dim value As Long

value = instance.LogisticsLocationExtRecordId

instance.LogisticsLocationExtRecordId = value
```

``` csharp
[ReadOnlyAttribute("LOGISTICSLOCATIONEXTRECID")]
[DataMemberAttribute]
[ColumnAttribute("LOGISTICSLOCATIONEXTRECID")]
public long LogisticsLocationExtRecordId { get; set; }
```

``` c++
[ReadOnlyAttribute(L"LOGISTICSLOCATIONEXTRECID")]
[DataMemberAttribute]
[ColumnAttribute(L"LOGISTICSLOCATIONEXTRECID")]
public:
property long long LogisticsLocationExtRecordId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The logistics locationExt record identifier.  

## See Also

#### Reference

[Address Class](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


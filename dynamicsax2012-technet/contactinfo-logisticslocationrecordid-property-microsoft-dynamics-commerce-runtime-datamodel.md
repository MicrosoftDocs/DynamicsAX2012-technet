---
title: ContactInfo.LogisticsLocationRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LogisticsLocationRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ContactInfo.LogisticsLocationRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.contactinfo.logisticslocationrecordid(v=AX.60)
ms:contentKeyID: 62214521
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ContactInfo.LogisticsLocationRecordId
dev_langs:
- CSharp
- C++
- VB
---

# LogisticsLocationRecordId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the logistics location identifier for a contact.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("LOGISTICSLOCATIONRECORDID")> _
<DataMemberAttribute> _
Public Property LogisticsLocationRecordId As Long
    Get
    Set
'Usage
Dim instance As ContactInfo
Dim value As Long

value = instance.LogisticsLocationRecordId

instance.LogisticsLocationRecordId = value
```

``` csharp
[ColumnAttribute("LOGISTICSLOCATIONRECORDID")]
[DataMemberAttribute]
public long LogisticsLocationRecordId { get; set; }
```

``` c++
[ColumnAttribute(L"LOGISTICSLOCATIONRECORDID")]
[DataMemberAttribute]
public:
property long long LogisticsLocationRecordId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[ContactInfo Class](contactinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


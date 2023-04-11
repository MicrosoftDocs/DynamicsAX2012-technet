---
title: ReportZone.ReportRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReportRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReportZone.ReportRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reportzone.reportrecordid(v=AX.60)
ms:contentKeyID: 62213315
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReportZone.ReportRecordId
dev_langs:
- CSharp
- C++
- VB
---

# ReportRecordId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the value of report identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("REPORT")> _
Public Property ReportRecordId As Long
    Get
    Set
'Usage
Dim instance As ReportZone
Dim value As Long

value = instance.ReportRecordId

instance.ReportRecordId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("REPORT")]
public long ReportRecordId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"REPORT")]
public:
property long long ReportRecordId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[ReportZone Class](reportzone-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


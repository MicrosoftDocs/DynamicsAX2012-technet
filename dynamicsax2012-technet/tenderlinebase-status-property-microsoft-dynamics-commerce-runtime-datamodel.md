---
title: TenderLineBase.Status Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Status Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineBase.Status
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tenderlinebase.status(v=AX.60)
ms:contentKeyID: 62208076
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineBase.Status
dev_langs:
- CSharp
- C++
- VB
---

# Status Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the status of the tender line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("STATUS")> _
<IgnoreDataMemberAttribute> _
Public Property Status As TenderLineStatus
    Get
    Set
'Usage
Dim instance As TenderLineBase
Dim value As TenderLineStatus

value = instance.Status

instance.Status = value
```

``` csharp
[ColumnAttribute("STATUS")]
[IgnoreDataMemberAttribute]
public TenderLineStatus Status { get; set; }
```

``` c++
[ColumnAttribute(L"STATUS")]
[IgnoreDataMemberAttribute]
public:
property TenderLineStatus Status {
    TenderLineStatus get ();
    void set (TenderLineStatus value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineStatus](tenderlinestatus-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [TenderLineStatus](tenderlinestatus-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[TenderLineBase Class](tenderlinebase-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


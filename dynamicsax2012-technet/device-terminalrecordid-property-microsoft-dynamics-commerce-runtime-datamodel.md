---
title: Device.TerminalRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TerminalRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Device.TerminalRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.device.terminalrecordid(v=AX.60)
ms:contentKeyID: 62211554
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Device.TerminalRecordId
dev_langs:
- CSharp
- C++
- VB
---

# TerminalRecordId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the associated terminal record identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TERMINALRECID")> _
<DataMemberAttribute> _
Public Property TerminalRecordId As Long
    Get
    Set
'Usage
Dim instance As Device
Dim value As Long

value = instance.TerminalRecordId

instance.TerminalRecordId = value
```

``` csharp
[ColumnAttribute("TERMINALRECID")]
[DataMemberAttribute]
public long TerminalRecordId { get; set; }
```

``` c++
[ColumnAttribute(L"TERMINALRECID")]
[DataMemberAttribute]
public:
property long long TerminalRecordId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The terminal record identifier.  

## See Also

#### Reference

[Device Class](device-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


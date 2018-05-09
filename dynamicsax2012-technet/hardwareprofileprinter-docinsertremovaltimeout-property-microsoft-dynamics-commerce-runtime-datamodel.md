---
title: HardwareProfilePrinter.DocInsertRemovalTimeout Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DocInsertRemovalTimeout Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfilePrinter.DocInsertRemovalTimeout
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofileprinter.docinsertremovaltimeout(v=AX.60)
ms:contentKeyID: 62202692
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfilePrinter.DocInsertRemovalTimeout
dev_langs:
- CSharp
- C++
- VB
---

# DocInsertRemovalTimeout Property

Gets or sets the document insert removal timeout.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PRINTERDOCINSERTREMOVALTIMEOUTVALUE")> _
<DataMemberAttribute> _
Public Property DocInsertRemovalTimeout As Integer
    Get
    Set
'Usage
Dim instance As HardwareProfilePrinter
Dim value As Integer

value = instance.DocInsertRemovalTimeout

instance.DocInsertRemovalTimeout = value
```

``` csharp
[ColumnAttribute("PRINTERDOCINSERTREMOVALTIMEOUTVALUE")]
[DataMemberAttribute]
public int DocInsertRemovalTimeout { get; set; }
```

``` c++
[ColumnAttribute(L"PRINTERDOCINSERTREMOVALTIMEOUTVALUE")]
[DataMemberAttribute]
public:
property int DocInsertRemovalTimeout {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
The timeout value.  

## See Also

#### Reference

[HardwareProfilePrinter Class](hardwareprofileprinter-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


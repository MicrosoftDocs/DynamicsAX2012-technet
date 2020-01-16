---
title: ShiftDataQueryCriteria.TerminalId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TerminalId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftDataQueryCriteria.TerminalId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shiftdataquerycriteria.terminalid(v=AX.60)
ms:contentKeyID: 65319272
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftDataQueryCriteria.TerminalId
dev_langs:
- CSharp
- C++
- VB
---

# TerminalId Property

Gets or sets the terminal identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TerminalId As String
    Get
    Set
'Usage
Dim instance As ShiftDataQueryCriteria
Dim value As String

value = instance.TerminalId

instance.TerminalId = value
```

``` csharp
[DataMemberAttribute]
public string TerminalId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ TerminalId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ShiftDataQueryCriteria Class](shiftdataquerycriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


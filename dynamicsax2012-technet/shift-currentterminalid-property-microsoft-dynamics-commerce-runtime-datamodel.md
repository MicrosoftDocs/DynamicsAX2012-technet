---
title: Shift.CurrentTerminalId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CurrentTerminalId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.CurrentTerminalId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shift.currentterminalid(v=AX.60)
ms:contentKeyID: 62210794
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.CurrentTerminalId
dev_langs:
- CSharp
- C++
- VB
---

# CurrentTerminalId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the current terminal identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CURRENTTERMINALID")> _
<DataMemberAttribute> _
Public Property CurrentTerminalId As String
    Get
    Set
'Usage
Dim instance As Shift
Dim value As String

value = instance.CurrentTerminalId

instance.CurrentTerminalId = value
```

``` csharp
[ColumnAttribute("CURRENTTERMINALID")]
[DataMemberAttribute]
public string CurrentTerminalId { get; set; }
```

``` c++
[ColumnAttribute(L"CURRENTTERMINALID")]
[DataMemberAttribute]
public:
property String^ CurrentTerminalId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## Remarks

CurrentTerminalId is the identifier of current terminal operating the shift.

## See Also

#### Reference

[Shift Class](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


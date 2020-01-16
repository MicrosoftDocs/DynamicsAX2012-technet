---
title: Transaction.ShiftTerminalId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ShiftTerminalId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Transaction.ShiftTerminalId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.transaction.shiftterminalid(v=AX.60)
ms:contentKeyID: 62211447
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Transaction.ShiftTerminalId
dev_langs:
- CSharp
- C++
- VB
---

# ShiftTerminalId Property

Gets or sets the shift terminal identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("BATCHTERMINALID")> _
Public Property ShiftTerminalId As String
    Get
    Set
'Usage
Dim instance As Transaction
Dim value As String

value = instance.ShiftTerminalId

instance.ShiftTerminalId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("BATCHTERMINALID")]
public string ShiftTerminalId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"BATCHTERMINALID")]
public:
property String^ ShiftTerminalId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[Transaction Class](transaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


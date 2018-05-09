---
title: ReasonCodeLine.StatementCode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: StatementCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeLine.StatementCode
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncodeline.statementcode(v=AX.60)
ms:contentKeyID: 62213110
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeLine.StatementCode
dev_langs:
- CSharp
- C++
- VB
---

# StatementCode Property

Gets or sets the statement code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("STATEMENTCODE")> _
<DataMemberAttribute> _
Public Property StatementCode As String
    Get
    Set
'Usage
Dim instance As ReasonCodeLine
Dim value As String

value = instance.StatementCode

instance.StatementCode = value
```

``` csharp
[ColumnAttribute("STATEMENTCODE")]
[DataMemberAttribute]
public string StatementCode { get; set; }
```

``` c++
[ColumnAttribute(L"STATEMENTCODE")]
[DataMemberAttribute]
public:
property String^ StatementCode {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The statement code.  

## See Also

#### Reference

[ReasonCodeLine Class](reasoncodeline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


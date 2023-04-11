---
title: SalesTransaction.StatementCode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: StatementCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.StatementCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.statementcode(v=AX.60)
ms:contentKeyID: 62202109
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.StatementCode
dev_langs:
- CSharp
- C++
- VB
---

# StatementCode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the statement code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("STATEMENTCODE")> _
<DataMemberAttribute> _
<ReadOnlyAttribute("STATEMENTCODE")> _
Public Property StatementCode As String
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As String

value = instance.StatementCode

instance.StatementCode = value
```

``` csharp
[ColumnAttribute("STATEMENTCODE")]
[DataMemberAttribute]
[ReadOnlyAttribute("STATEMENTCODE")]
public string StatementCode { get; set; }
```

``` c++
[ColumnAttribute(L"STATEMENTCODE")]
[DataMemberAttribute]
[ReadOnlyAttribute(L"STATEMENTCODE")]
public:
property String^ StatementCode {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


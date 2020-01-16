---
title: Transaction.Id Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Id Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Transaction.Id
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.transaction.id(v=AX.60)
ms:contentKeyID: 62211473
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Transaction.Id
dev_langs:
- CSharp
- C++
- VB
---

# Id Property

Gets or sets the sales transaction identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<KeyAttribute> _
<ColumnAttribute("TRANSACTIONID")> _
Public Property Id As String
    Get
    Set
'Usage
Dim instance As Transaction
Dim value As String

value = instance.Id

instance.Id = value
```

``` csharp
[DataMemberAttribute]
[KeyAttribute]
[ColumnAttribute("TRANSACTIONID")]
public string Id { get; set; }
```

``` c++
[DataMemberAttribute]
[KeyAttribute]
[ColumnAttribute(L"TRANSACTIONID")]
public:
property String^ Id {
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


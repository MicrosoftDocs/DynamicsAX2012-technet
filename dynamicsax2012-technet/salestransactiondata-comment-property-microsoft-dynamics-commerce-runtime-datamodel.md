---
title: SalesTransactionData.Comment Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Comment Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransactionData.Comment
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransactiondata.comment(v=AX.60)
ms:contentKeyID: 62212522
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransactionData.Comment
dev_langs:
- CSharp
- C++
- VB
---

# Comment Property

Gets or sets the transaction comment identifier. Cannot be more than 60 characters.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("COMMENT")> _
Public Property Comment As String
    Get
    Set
'Usage
Dim instance As SalesTransactionData
Dim value As String

value = instance.Comment

instance.Comment = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("COMMENT")]
public string Comment { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"COMMENT")]
public:
property String^ Comment {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[SalesTransactionData Class](salestransactiondata-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


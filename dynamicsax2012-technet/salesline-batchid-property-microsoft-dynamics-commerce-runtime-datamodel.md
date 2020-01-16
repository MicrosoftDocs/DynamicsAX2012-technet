---
title: SalesLine.BatchId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: BatchId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.BatchId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.batchid(v=AX.60)
ms:contentKeyID: 62212953
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.BatchId
dev_langs:
- CSharp
- C++
- VB
---

# BatchId Property

Gets or sets the batch id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("INVENTBATCHID")> _
Public Property BatchId As String
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As String

value = instance.BatchId

instance.BatchId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("INVENTBATCHID")]
public string BatchId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"INVENTBATCHID")]
public:
property String^ BatchId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[SalesLine Class](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


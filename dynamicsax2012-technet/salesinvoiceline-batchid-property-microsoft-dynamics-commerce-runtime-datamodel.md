---
title: SalesInvoiceLine.BatchId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: BatchId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceLine.BatchId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesinvoiceline.batchid(v=AX.60)
ms:contentKeyID: 62205759
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceLine.BatchId
dev_langs:
- CSharp
- C++
- VB
---

# BatchId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the batch identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("INVENTBATCHID")> _
<DataMemberAttribute> _
Public Property BatchId As String
    Get
    Set
'Usage
Dim instance As SalesInvoiceLine
Dim value As String

value = instance.BatchId

instance.BatchId = value
```

``` csharp
[ColumnAttribute("INVENTBATCHID")]
[DataMemberAttribute]
public string BatchId { get; set; }
```

``` c++
[ColumnAttribute(L"INVENTBATCHID")]
[DataMemberAttribute]
public:
property String^ BatchId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The batch identifier.  

## See Also

#### Reference

[SalesInvoiceLine Class](salesinvoiceline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


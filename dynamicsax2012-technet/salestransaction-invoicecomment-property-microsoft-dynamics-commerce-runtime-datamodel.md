---
title: SalesTransaction.InvoiceComment Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InvoiceComment Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.InvoiceComment
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.invoicecomment(v=AX.60)
ms:contentKeyID: 65322537
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.InvoiceComment
dev_langs:
- CSharp
- C++
- VB
---

# InvoiceComment Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("INVOICECOMMENT")> _
Public Property InvoiceComment As String
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As String

value = instance.InvoiceComment

instance.InvoiceComment = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("INVOICECOMMENT")]
public string InvoiceComment { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"INVOICECOMMENT")]
public:
property String^ InvoiceComment {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


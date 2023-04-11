---
title: SalesInvoice.Id Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Id Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoice.Id
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesinvoice.id(v=AX.60)
ms:contentKeyID: 62203109
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoice.Id
dev_langs:
- CSharp
- C++
- VB
---

# Id Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the invoice identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("INVOICEID")> _
<DataMemberAttribute> _
Public Property Id As String
    Get
    Set
'Usage
Dim instance As SalesInvoice
Dim value As String

value = instance.Id

instance.Id = value
```

``` csharp
[ColumnAttribute("INVOICEID")]
[DataMemberAttribute]
public string Id { get; set; }
```

``` c++
[ColumnAttribute(L"INVOICEID")]
[DataMemberAttribute]
public:
property String^ Id {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The invoice identifier.  

## See Also

#### Reference

[SalesInvoice Class](salesinvoice-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


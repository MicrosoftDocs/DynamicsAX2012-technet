---
title: SalesInvoice.Account Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Account Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoice.Account
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesinvoice.account(v=AX.60)
ms:contentKeyID: 62207623
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoice.Account
dev_langs:
- CSharp
- C++
- VB
---

# Account Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the invoice account.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("INVOICEACCOUNT")> _
<DataMemberAttribute> _
Public Property Account As String
    Get
    Set
'Usage
Dim instance As SalesInvoice
Dim value As String

value = instance.Account

instance.Account = value
```

``` csharp
[ColumnAttribute("INVOICEACCOUNT")]
[DataMemberAttribute]
public string Account { get; set; }
```

``` c++
[ColumnAttribute(L"INVOICEACCOUNT")]
[DataMemberAttribute]
public:
property String^ Account {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The invoice account.  

## See Also

#### Reference

[SalesInvoice Class](salesinvoice-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


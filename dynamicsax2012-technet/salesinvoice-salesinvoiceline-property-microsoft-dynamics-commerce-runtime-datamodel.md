---
title: SalesInvoice.SalesInvoiceLine Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SalesInvoiceLine Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoice.SalesInvoiceLine
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesinvoice.salesinvoiceline(v=AX.60)
ms:contentKeyID: 62212454
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoice.SalesInvoiceLine
dev_langs:
- CSharp
- C++
- VB
---

# SalesInvoiceLine Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the customer invoice transactions.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SalesInvoiceLine As IList(Of SalesInvoiceLine)
    Get
    Set
'Usage
Dim instance As SalesInvoice
Dim value As IList(Of SalesInvoiceLine)

value = instance.SalesInvoiceLine

instance.SalesInvoiceLine = value
```

``` csharp
[DataMemberAttribute]
public IList<SalesInvoiceLine> SalesInvoiceLine { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IList<SalesInvoiceLine^>^ SalesInvoiceLine {
    IList<SalesInvoiceLine^>^ get ();
    void set (IList<SalesInvoiceLine^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[SalesInvoiceLine](salesinvoiceline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IList\<T\>](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\)).  

## See Also

#### Reference

[SalesInvoice Class](salesinvoice-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


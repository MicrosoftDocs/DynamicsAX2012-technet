---
title: SalesLine.ReturnQuantity Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReturnQuantity Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.ReturnQuantity
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.returnquantity(v=AX.60)
ms:contentKeyID: 62210159
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.ReturnQuantity
dev_langs:
- CSharp
- C++
- VB
---

# ReturnQuantity Property

Gets or sets the return item quantity.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("RETURNQTY")> _
Public Property ReturnQuantity As Decimal
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As Decimal

value = instance.ReturnQuantity

instance.ReturnQuantity = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("RETURNQTY")]
public decimal ReturnQuantity { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"RETURNQTY")]
public:
property Decimal ReturnQuantity {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The return quantity.  

## See Also

#### Reference

[SalesLine Class](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


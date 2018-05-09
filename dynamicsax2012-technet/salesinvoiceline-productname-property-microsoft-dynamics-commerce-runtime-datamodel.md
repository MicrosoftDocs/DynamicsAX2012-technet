---
title: SalesInvoiceLine.ProductName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceLine.ProductName
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.salesinvoiceline.productname(v=AX.60)
ms:contentKeyID: 62213820
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceLine.ProductName
dev_langs:
- CSharp
- C++
- VB
---

# ProductName Property

Gets or sets the product name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ECORESPRODUCTNAME")> _
Public Property ProductName As String
    Get
    Set
'Usage
Dim instance As SalesInvoiceLine
Dim value As String

value = instance.ProductName

instance.ProductName = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ECORESPRODUCTNAME")]
public string ProductName { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ECORESPRODUCTNAME")]
public:
property String^ ProductName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The product name.  

## See Also

#### Reference

[SalesInvoiceLine Class](salesinvoiceline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


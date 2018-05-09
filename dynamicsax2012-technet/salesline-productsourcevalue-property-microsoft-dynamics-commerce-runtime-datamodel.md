---
title: SalesLine.ProductSourceValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductSourceValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.ProductSourceValue
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.productsourcevalue(v=AX.60)
ms:contentKeyID: 62206692
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.ProductSourceValue
dev_langs:
- CSharp
- C++
- VB
---

# ProductSourceValue Property

Gets or sets the value of the ProductSource enum. Used by OData only.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ProductSourceValue As Integer
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As Integer

value = instance.ProductSourceValue

instance.ProductSourceValue = value
```

``` csharp
[DataMemberAttribute]
public int ProductSourceValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int ProductSourceValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[SalesLine Class](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


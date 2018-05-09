---
title: ProductIdentity.ProductSearchName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductSearchName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductIdentity.ProductSearchName
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.productidentity.productsearchname(v=AX.60)
ms:contentKeyID: 62214020
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductIdentity.ProductSearchName
dev_langs:
- CSharp
- C++
- VB
---

# ProductSearchName Property

Gets the search name of the product.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("SEARCHNAME")> _
<DataMemberAttribute> _
Public Property ProductSearchName As String
    Get
    Friend Set
'Usage
Dim instance As ProductIdentity
Dim value As String

value = instance.ProductSearchName
```

``` csharp
[ColumnAttribute("SEARCHNAME")]
[DataMemberAttribute]
public string ProductSearchName { get; internal set; }
```

``` c++
[ColumnAttribute(L"SEARCHNAME")]
[DataMemberAttribute]
public:
property String^ ProductSearchName {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The search name of the product.  

## See Also

#### Reference

[ProductIdentity Class](productidentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


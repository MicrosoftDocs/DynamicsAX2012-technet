---
title: ProductIdentity.ProductDisplayNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductDisplayNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductIdentity.ProductDisplayNumber
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.productidentity.productdisplaynumber(v=AX.60)
ms:contentKeyID: 62207977
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductIdentity.ProductDisplayNumber
dev_langs:
- CSharp
- C++
- VB
---

# ProductDisplayNumber Property

Gets the product's display number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DISPLAYPRODUCTNUMBER")> _
<DataMemberAttribute> _
Public Property ProductDisplayNumber As String
    Get
    Friend Set
'Usage
Dim instance As ProductIdentity
Dim value As String

value = instance.ProductDisplayNumber
```

``` csharp
[ColumnAttribute("DISPLAYPRODUCTNUMBER")]
[DataMemberAttribute]
public string ProductDisplayNumber { get; internal set; }
```

``` c++
[ColumnAttribute(L"DISPLAYPRODUCTNUMBER")]
[DataMemberAttribute]
public:
property String^ ProductDisplayNumber {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The description.  

## See Also

#### Reference

[ProductIdentity Class](productidentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


---
title: Product.SearchName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SearchName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.SearchName
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.product.searchname(v=AX.60)
ms:contentKeyID: 65316968
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.SearchName
dev_langs:
- CSharp
- C++
- VB
---

# SearchName Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SearchName As String
    Get
    Set
'Usage
Dim instance As Product
Dim value As String

value = instance.SearchName

instance.SearchName = value
```

``` csharp
[DataMemberAttribute]
public string SearchName { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ SearchName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[Product Class](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


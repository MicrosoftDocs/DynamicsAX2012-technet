---
title: ProductSearchCriteria.SearchCondition Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SearchCondition Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria.SearchCondition
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.productsearchcriteria.searchcondition(v=AX.60)
ms:contentKeyID: 62212048
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria.SearchCondition
dev_langs:
- CSharp
- C++
- VB
---

# SearchCondition Property

Gets or sets the search condition to search for products.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SearchCondition As String
    Get
    Set
'Usage
Dim instance As ProductSearchCriteria
Dim value As String

value = instance.SearchCondition

instance.SearchCondition = value
```

``` csharp
[DataMemberAttribute]
public string SearchCondition { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ SearchCondition {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ProductSearchCriteria Class](productsearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


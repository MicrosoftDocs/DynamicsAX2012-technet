---
title: ProductSearchCriteria.Barcodes Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Barcodes Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria.Barcodes
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productsearchcriteria.barcodes(v=AX.60)
ms:contentKeyID: 62204971
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria.Barcodes
dev_langs:
- CSharp
- C++
- VB
---

# Barcodes Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the barcodes by which to search for products.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Barcodes As IList(Of String)
    Get
    Set
'Usage
Dim instance As ProductSearchCriteria
Dim value As IList(Of String)

value = instance.Barcodes

instance.Barcodes = value
```

``` csharp
[DataMemberAttribute]
public IList<string> Barcodes { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IList<String^>^ Barcodes {
    IList<String^>^ get ();
    void set (IList<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
Returns [IList\<T\>](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\)).  

## See Also

#### Reference

[ProductSearchCriteria Class](productsearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


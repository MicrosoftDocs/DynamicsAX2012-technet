---
title: CatalogSearchCriteria.Keywords Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Keywords Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CatalogSearchCriteria.Keywords
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.catalogsearchcriteria.keywords(v=AX.60)
ms:contentKeyID: 62211097
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CatalogSearchCriteria.Keywords
dev_langs:
- CSharp
- C++
- VB
---

# Keywords Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the keywords by which to search for catalogs.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Keywords As IList(Of String)
    Get
    Set
'Usage
Dim instance As CatalogSearchCriteria
Dim value As IList(Of String)

value = instance.Keywords

instance.Keywords = value
```

``` csharp
[DataMemberAttribute]
public IList<string> Keywords { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IList<String^>^ Keywords {
    IList<String^>^ get ();
    void set (IList<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
Returns [IList\<T\>](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\)).  

## See Also

#### Reference

[CatalogSearchCriteria Class](catalogsearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


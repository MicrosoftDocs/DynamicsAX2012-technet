---
title: CommerceEntitySearchResult(T).Results Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Results Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntitySearchResult`1.Results
ms:mtpsurl: https://technet.microsoft.com/library/Dn697410(v=AX.60)
ms:contentKeyID: 62209300
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntitySearchResult`1.Results
dev_langs:
- CSharp
- C++
- VB
---

# Results Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the results associated with this query.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Results As ReadOnlyCollection(Of T)
    Get
    Set
'Usage
Dim instance As CommerceEntitySearchResult
Dim value As ReadOnlyCollection(Of T)

value = instance.Results

instance.Results = value
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<T> Results { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<T>^ Results {
    ReadOnlyCollection<T>^ get ();
    void set (ReadOnlyCollection<T>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[T](commerceentitysearchresult-t-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The search results of this query.  

## See Also

#### Reference

[CommerceEntitySearchResult\<T\> Class](commerceentitysearchresult-t-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


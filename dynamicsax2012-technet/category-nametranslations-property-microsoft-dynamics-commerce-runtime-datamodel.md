---
title: Category.NameTranslations Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: NameTranslations Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Category.NameTranslations
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.category.nametranslations(v=AX.60)
ms:contentKeyID: 49832364
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Category.NameTranslations
dev_langs:
- CSharp
- C++
- VB
---

# NameTranslations Property

Gets or sets the collection of category name translations.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property NameTranslations As IEnumerable(Of TextValueTranslation)
    Get
    Set
'Usage
Dim instance As Category
Dim value As IEnumerable(Of TextValueTranslation)

value = instance.NameTranslations

instance.NameTranslations = value
```

``` csharp
[DataMemberAttribute]
public IEnumerable<TextValueTranslation> NameTranslations { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<TextValueTranslation^>^ NameTranslations {
    IEnumerable<TextValueTranslation^>^ get ();
    void set (IEnumerable<TextValueTranslation^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[TextValueTranslation](textvaluetranslation-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[Category Class](category-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


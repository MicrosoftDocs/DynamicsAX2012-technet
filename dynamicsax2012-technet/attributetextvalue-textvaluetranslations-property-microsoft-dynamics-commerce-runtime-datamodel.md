---
title: AttributeTextValue.TextValueTranslations Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TextValueTranslations Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeTextValue.TextValueTranslations
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.attributetextvalue.textvaluetranslations(v=AX.60)
ms:contentKeyID: 49837908
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeTextValue.TextValueTranslations
dev_langs:
- CSharp
- C++
- VB
---

# TextValueTranslations Property

Gets or sets the translations of the text value

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TextValueTranslations As IEnumerable(Of TextValueTranslation)
    Get
    Set
'Usage
Dim instance As AttributeTextValue
Dim value As IEnumerable(Of TextValueTranslation)

value = instance.TextValueTranslations

instance.TextValueTranslations = value
```

``` csharp
[DataMemberAttribute]
public IEnumerable<TextValueTranslation> TextValueTranslations { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<TextValueTranslation^>^ TextValueTranslations {
    IEnumerable<TextValueTranslation^>^ get ();
    void set (IEnumerable<TextValueTranslation^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[TextValueTranslation](textvaluetranslation-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[AttributeTextValue Class](attributetextvalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


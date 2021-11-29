---
title: AttributeCategory.CategoryAttributeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CategoryAttributeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeCategory.CategoryAttributeValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.attributecategory.categoryattributevalue(v=AX.60)
ms:contentKeyID: 49831455
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeCategory.CategoryAttributeValue
dev_langs:
- CSharp
- C++
- VB
---

# CategoryAttributeValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the category attribute value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CategoryAttributeValue As AttributeValueBase
    Get
    Set
'Usage
Dim instance As AttributeCategory
Dim value As AttributeValueBase

value = instance.CategoryAttributeValue

instance.CategoryAttributeValue = value
```

``` csharp
[DataMemberAttribute]
public AttributeValueBase CategoryAttributeValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property AttributeValueBase^ CategoryAttributeValue {
    AttributeValueBase^ get ();
    void set (AttributeValueBase^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeValueBase](attributevaluebase-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [AttributeValueBase](attributevaluebase-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[AttributeCategory Class](attributecategory-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


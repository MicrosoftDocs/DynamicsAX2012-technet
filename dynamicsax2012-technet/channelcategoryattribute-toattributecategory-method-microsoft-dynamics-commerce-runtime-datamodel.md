---
title: ChannelCategoryAttribute.ToAttributeCategory Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ToAttributeCategory Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelCategoryAttribute.ToAttributeCategory(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channelcategoryattribute.toattributecategory(v=AX.60)
ms:contentKeyID: 65323018
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelCategoryAttribute.ToAttributeCategory
dev_langs:
- CSharp
- C++
- VB
---

# ToAttributeCategory Method

Converts this channel category attribute to a category attribute.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Function ToAttributeCategory ( _
    languageId As String _
) As AttributeCategory
'Usage
Dim instance As ChannelCategoryAttribute
Dim languageId As String
Dim returnValue As AttributeCategory

returnValue = instance.ToAttributeCategory(languageId)
```

``` csharp
public AttributeCategory ToAttributeCategory(
    string languageId
)
```

``` c++
public:
AttributeCategory^ ToAttributeCategory(
    String^ languageId
)
```

#### Parameters

  - languageId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeCategory](attributecategory-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The category attribute.  

## See Also

#### Reference

[ChannelCategoryAttribute Class](channelcategoryattribute-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


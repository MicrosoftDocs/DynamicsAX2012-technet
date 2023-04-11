---
title: AttributeBase Class (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AttributeBase Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeBase
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.attributebase(v=AX.60)
ms:contentKeyID: 49843492
author: tfehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeBase
dev_langs:
- CSharp
- C++
- VB
---

# AttributeBase Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Represents an attribute.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public MustInherit Class AttributeBase _
    Inherits CommerceEntity
'Usage
Dim instance As AttributeBase
```

``` csharp
[DataContractAttribute]
public abstract class AttributeBase : CommerceEntity
```

``` c++
[DataContractAttribute]
public ref class AttributeBase abstract : public CommerceEntity
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
    Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeBase  
      [Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeCategory](attributecategory-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeProduct](attributeproduct-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelAttribute](channelattribute-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelAttributeView](channelattributeview-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelCategoryAttribute](channelcategoryattribute-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


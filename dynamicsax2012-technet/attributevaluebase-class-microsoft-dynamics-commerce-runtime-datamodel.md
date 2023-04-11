---
title: AttributeValueBase Class (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AttributeValueBase Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeValueBase
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.attributevaluebase(v=AX.60)
ms:contentKeyID: 49829715
author: tonyafehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeValueBase
dev_langs:
- CSharp
- C++
- VB
---

# AttributeValueBase Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Represents the base type for attributes with values.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public MustInherit Class AttributeValueBase _
    Inherits CommerceEntity
'Usage
Dim instance As AttributeValueBase
```

``` csharp
[DataContractAttribute]
public abstract class AttributeValueBase : CommerceEntity
```

``` c++
[DataContractAttribute]
public ref class AttributeValueBase abstract : public CommerceEntity
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
    Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeValueBase  
      [Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeBooleanValue](attributebooleanvalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeCurrencyValue](attributecurrencyvalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeDateTimeOffsetValue](attributedatetimeoffsetvalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeFloatValue](attributefloatvalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeIntValue](attributeintvalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeRichMediaValue](attributerichmediavalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeTextValue](attributetextvalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


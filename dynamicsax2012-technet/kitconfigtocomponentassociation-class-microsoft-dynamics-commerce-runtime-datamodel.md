---
title: KitConfigToComponentAssociation Class (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: KitConfigToComponentAssociation Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.KitConfigToComponentAssociation
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.kitconfigtocomponentassociation(v=AX.60)
ms:contentKeyID: 65322228
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.KitConfigToComponentAssociation
dev_langs:
- CSharp
- C++
- VB
---

# KitConfigToComponentAssociation Class

Represents the association between the products contained in a kit variant and the kit variant, i.e. contains information about the product used in a kit variant, as a constituent, and its 'kit related' properties like quantity and unit of the product used in a kit variant line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Class KitConfigToComponentAssociation _
    Inherits CommerceEntity
'Usage
Dim instance As KitConfigToComponentAssociation
```

``` csharp
[DataContractAttribute]
public class KitConfigToComponentAssociation : CommerceEntity
```

``` c++
[DataContractAttribute]
public ref class KitConfigToComponentAssociation : public CommerceEntity
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
    Microsoft.Dynamics.Commerce.Runtime.DataModel.KitConfigToComponentAssociation  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


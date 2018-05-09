---
title: AttributeBase.Group Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Group Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeBase.Group
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.attributebase.group(v=AX.60)
ms:contentKeyID: 49840976
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeBase.Group
dev_langs:
- CSharp
- C++
- VB
---

# Group Property

Gets the attribute group information.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Group As AttributeGroup
    Get
    Friend Set
'Usage
Dim instance As AttributeBase
Dim value As AttributeGroup

value = instance.Group
```

``` csharp
[DataMemberAttribute]
public AttributeGroup Group { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property AttributeGroup^ Group {
    AttributeGroup^ get ();
    internal: void set (AttributeGroup^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeGroup](attributegroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [AttributeGroup](attributegroup-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[AttributeBase Class](attributebase-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


---
title: CommerceEntity.ExtensionProperties Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ExtensionProperties Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity.ExtensionProperties
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.commerceentity.extensionproperties(v=AX.60)
ms:contentKeyID: 62206904
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity.ExtensionProperties
dev_langs:
- CSharp
- C++
- VB
---

# ExtensionProperties Property

Gets or sets the extension properties.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Overridable Property ExtensionProperties As ICollection(Of CommerceProperty)
    Get
    Set
'Usage
Dim instance As CommerceEntity
Dim value As ICollection(Of CommerceProperty)

value = instance.ExtensionProperties

instance.ExtensionProperties = value
```

``` csharp
[DataMemberAttribute]
public virtual ICollection<CommerceProperty> ExtensionProperties { get; set; }
```

``` c++
[DataMemberAttribute]
public:
virtual property ICollection<CommerceProperty^>^ ExtensionProperties {
    ICollection<CommerceProperty^>^ get ();
    void set (ICollection<CommerceProperty^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[CommerceProperty](commerceproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ICollection\<T\>](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\)).  

## See Also

#### Reference

[CommerceEntity Class](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


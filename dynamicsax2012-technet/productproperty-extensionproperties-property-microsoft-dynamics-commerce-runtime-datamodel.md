---
title: ProductProperty.ExtensionProperties Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ExtensionProperties Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductProperty.ExtensionProperties
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.productproperty.extensionproperties(v=AX.60)
ms:contentKeyID: 65318063
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductProperty.ExtensionProperties
dev_langs:
- CSharp
- C++
- VB
---

# ExtensionProperties Property

This member overrides [CommerceEntity.ExtensionProperties](commerceentity-extensionproperties-property-microsoft-dynamics-commerce-runtime-datamodel.md).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Overrides Property ExtensionProperties As ICollection(Of CommerceProperty)
    Get
    Set
'Usage
Dim instance As ProductProperty
Dim value As ICollection(Of CommerceProperty)

value = instance.ExtensionProperties

instance.ExtensionProperties = value
```

``` csharp
[DataMemberAttribute]
public override ICollection<CommerceProperty> ExtensionProperties { get; set; }
```

``` c++
[DataMemberAttribute]
public:
virtual property ICollection<CommerceProperty^>^ ExtensionProperties {
    ICollection<CommerceProperty^>^ get () override;
    void set (ICollection<CommerceProperty^>^ value) override;
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/en-us/library/92t2ye13\(v=ax.60\))\<[CommerceProperty](commerceproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ProductProperty Class](productproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


---
title: CommerceProperty.Value Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Value Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceProperty.Value
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.commerceproperty.value(v=AX.60)
ms:contentKeyID: 62207720
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceProperty.Value
dev_langs:
- CSharp
- C++
- VB
---

# Value Property

Gets or sets the property value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Value As CommercePropertyValue
    Get
    Set
'Usage
Dim instance As CommerceProperty
Dim value As CommercePropertyValue

value = instance.Value

instance.Value = value
```

``` csharp
[DataMemberAttribute]
public CommercePropertyValue Value { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property CommercePropertyValue^ Value {
    CommercePropertyValue^ get ();
    void set (CommercePropertyValue^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommercePropertyValue](commercepropertyvalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [CommercePropertyValue](commercepropertyvalue-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[CommerceProperty Class](commerceproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


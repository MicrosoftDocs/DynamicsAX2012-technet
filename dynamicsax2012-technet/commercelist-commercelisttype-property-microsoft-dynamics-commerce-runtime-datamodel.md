---
title: CommerceList.CommerceListType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CommerceListType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceList.CommerceListType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.commercelist.commercelisttype(v=AX.60)
ms:contentKeyID: 62202845
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceList.CommerceListType
dev_langs:
- CSharp
- C++
- VB
---

# CommerceListType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the commerce list type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property CommerceListType As CommerceListType
    Get
    Set
'Usage
Dim instance As CommerceList
Dim value As CommerceListType

value = instance.CommerceListType

instance.CommerceListType = value
```

``` csharp
[IgnoreDataMemberAttribute]
public CommerceListType CommerceListType { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property CommerceListType CommerceListType {
    CommerceListType get ();
    void set (CommerceListType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceListType](commercelisttype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [CommerceListType](commercelisttype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[CommerceList Class](commercelist-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


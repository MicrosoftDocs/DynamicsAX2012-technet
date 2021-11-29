---
title: CommercePropertyValue Constructor (Type, Object) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CommercePropertyValue Constructor (Type, Object)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommercePropertyValue.#ctor(System.Type,System.Object)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.commercepropertyvalue.commercepropertyvalue(v=AX.60)
ms:contentKeyID: 62206716
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CommercePropertyValue Constructor (Type, Object)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [CommercePropertyValue](commercepropertyvalue-class-microsoft-dynamics-commerce-runtime-datamodel.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    propertyType As Type, _
    propertyValue As Object _
)
'Usage
Dim propertyType As Type
Dim propertyValue As Object

Dim instance As New CommercePropertyValue(propertyType, _
    propertyValue)
```

``` csharp
public CommercePropertyValue(
    Type propertyType,
    Object propertyValue
)
```

``` c++
public:
CommercePropertyValue(
    Type^ propertyType, 
    Object^ propertyValue
)
```

#### Parameters

  - propertyType  
    Type: [System.Type](https://technet.microsoft.com/library/42892f65\(v=ax.60\))  

<!-- end list -->

  - propertyValue  
    Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  

## See Also

#### Reference

[CommercePropertyValue Class](commercepropertyvalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[CommercePropertyValue Overload](commercepropertyvalue-constructor-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


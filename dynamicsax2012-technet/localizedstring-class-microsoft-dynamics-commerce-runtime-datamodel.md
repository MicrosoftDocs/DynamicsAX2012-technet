---
title: LocalizedString Class (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LocalizedString Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.LocalizedString
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.localizedstring(v=AX.60)
ms:contentKeyID: 62214567
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LocalizedString
dev_langs:
- CSharp
- C++
- VB
---

# LocalizedString Class

Represents a localized string for use in client applications.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Class LocalizedString _
    Inherits CommerceEntity
'Usage
Dim instance As LocalizedString
```

``` csharp
[DataContractAttribute]
public class LocalizedString : CommerceEntity
```

``` c++
[DataContractAttribute]
public ref class LocalizedString : public CommerceEntity
```

## Remarks

Because the entities are defined for the clients to consume through REST:

1\. The properties that are NOT relevant to the clients are not exposed (e.g. opt-in only).

2\. The mandatory properties are defined as basic properties.

3\. The optional properties are kept in the property bag.

4\. Localization is handled through the locale property (e.g. we only return properties of the locale that clients care about).

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
    Microsoft.Dynamics.Commerce.Runtime.DataModel.LocalizedString  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


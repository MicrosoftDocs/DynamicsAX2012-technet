---
title: FeatureNotSupportedException Class (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: FeatureNotSupportedException Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.FeatureNotSupportedException
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.featurenotsupportedexception(v=AX.60)
ms:contentKeyID: 65322284
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.FeatureNotSupportedException
dev_langs:
- CSharp
- C++
- VB
---

# FeatureNotSupportedException Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

DataValidationException used to indicate invalid data passed to the runtime and its components.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<KnownTypeAttribute(GetType(ReadOnlyCollection(Of DataValidationFailure)))> _
Public Class FeatureNotSupportedException _
    Inherits CommerceRuntimeException
'Usage
Dim instance As FeatureNotSupportedException
```

``` csharp
[KnownTypeAttribute(typeof(ReadOnlyCollection<DataValidationFailure>))]
public class FeatureNotSupportedException : CommerceRuntimeException
```

``` c++
[KnownTypeAttribute(typeof(ReadOnlyCollection<DataValidationFailure^>))]
public ref class FeatureNotSupportedException : public CommerceRuntimeException
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [System.Exception](https://technet.microsoft.com/library/c18k6c59\(v=ax.60\))  
    [Microsoft.Dynamics.Commerce.Runtime.CommerceRuntimeException](commerceruntimeexception-class-microsoft-dynamics-commerce-runtime.md)  
      Microsoft.Dynamics.Commerce.Runtime.FeatureNotSupportedException  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)


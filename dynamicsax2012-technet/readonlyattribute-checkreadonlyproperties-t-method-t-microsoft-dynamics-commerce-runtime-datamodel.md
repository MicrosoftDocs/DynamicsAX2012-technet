---
title: ReadOnlyAttribute.CheckReadOnlyProperties(T) Method (T) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CheckReadOnlyProperties(T) Method (T)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReadOnlyAttribute.CheckReadOnlyProperties``1(``0)
ms:mtpsurl: https://technet.microsoft.com/library/Dn696780(v=AX.60)
ms:contentKeyID: 62208168
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CheckReadOnlyProperties(T) Method (T)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Checks if properties checked as readonly have not been updated.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Shared Function CheckReadOnlyProperties(Of T As CommerceEntity) ( _
    newEntity As T _
) As Collection(Of DataValidationFailure)
'Usage
Dim newEntity As T
Dim returnValue As Collection(Of DataValidationFailure)

returnValue = ReadOnlyAttribute.CheckReadOnlyProperties(newEntity)
```

``` csharp
public static Collection<DataValidationFailure> CheckReadOnlyProperties<T>(
    T newEntity
)
where T : CommerceEntity
```

``` c++
public:
generic<typename T>
where T : CommerceEntity
static Collection<DataValidationFailure^>^ CheckReadOnlyProperties(
    T newEntity
)
```

#### Type Parameters

  - T

#### Parameters

  - newEntity  
    Type: T  

#### Return Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[DataValidationFailure](datavalidationfailure-class-microsoft-dynamics-commerce-runtime.md)\>  
A collection of data validation failures of type DataValidationErrors.PropertyUpdateNotAllowed in case there are differences in the values between newEntity and existingEntity.  

## See Also

#### Reference

[ReadOnlyAttribute Class](readonlyattribute-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[CheckReadOnlyProperties\<T\> Overload](readonlyattribute-checkreadonlyproperties-t-method-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


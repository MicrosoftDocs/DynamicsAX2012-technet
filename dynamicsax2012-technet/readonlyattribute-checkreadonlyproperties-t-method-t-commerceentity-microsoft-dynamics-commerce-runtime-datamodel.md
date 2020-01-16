---
title: ReadOnlyAttribute.CheckReadOnlyProperties(T) Method (T, CommerceEntity) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CheckReadOnlyProperties(T) Method (T, CommerceEntity)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReadOnlyAttribute.CheckReadOnlyProperties``1(``0,Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity)
ms:mtpsurl: https://technet.microsoft.com/library/Dn698431(v=AX.60)
ms:contentKeyID: 62211318
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CheckReadOnlyProperties(T) Method (T, CommerceEntity)

Checks if properties checked as readonly have not been updated.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Shared Function CheckReadOnlyProperties(Of T As CommerceEntity) ( _
    newEntity As T, _
    existingEntity As CommerceEntity _
) As Collection(Of DataValidationFailure)
'Usage
Dim newEntity As T
Dim existingEntity As CommerceEntity
Dim returnValue As Collection(Of DataValidationFailure)

returnValue = ReadOnlyAttribute.CheckReadOnlyProperties(newEntity, _
    existingEntity)
```

``` csharp
public static Collection<DataValidationFailure> CheckReadOnlyProperties<T>(
    T newEntity,
    CommerceEntity existingEntity
)
where T : CommerceEntity
```

``` c++
public:
generic<typename T>
where T : CommerceEntity
static Collection<DataValidationFailure^>^ CheckReadOnlyProperties(
    T newEntity, 
    CommerceEntity^ existingEntity
)
```

#### Type Parameters

  - T

#### Parameters

  - newEntity  
    Type: T  

<!-- end list -->

  - existingEntity  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[DataValidationFailure](datavalidationfailure-class-microsoft-dynamics-commerce-runtime.md)\>  
A collection of data validation failures of type DataValidationErrors.PropertyUpdateNotAllowed in case there are differences in the values between newEntity and existingEntity.  

## See Also

#### Reference

[ReadOnlyAttribute Class](readonlyattribute-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[CheckReadOnlyProperties\<T\> Overload](readonlyattribute-checkreadonlyproperties-t-method-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


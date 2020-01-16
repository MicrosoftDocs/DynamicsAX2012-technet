---
title: ReadOnlyAttribute.AssertPropertyNotChanged(T) Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AssertPropertyNotChanged(T) Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReadOnlyAttribute.AssertPropertyNotChanged``1(System.String,``0,Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity,Microsoft.Dynamics.Commerce.Runtime.DataValidationFailure@)
ms:mtpsurl: https://technet.microsoft.com/library/Dn718265(v=AX.60)
ms:contentKeyID: 62213135
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReadOnlyAttribute.AssertPropertyNotChanged``1
dev_langs:
- CSharp
- C++
- VB
---

# AssertPropertyNotChanged(T) Method

Checks whether the property has changed from the value present in the newEntity compared against the value in the existing entity.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Shared Function AssertPropertyNotChanged(Of T As CommerceEntity) ( _
    propertyName As String, _
    newEntity As T, _
    existingEntity As CommerceEntity, _
    <OutAttribute> ByRef failure As DataValidationFailure _
) As Boolean
'Usage
Dim propertyName As String
Dim newEntity As T
Dim existingEntity As CommerceEntity
Dim failure As DataValidationFailure
Dim returnValue As Boolean

returnValue = ReadOnlyAttribute.AssertPropertyNotChanged(propertyName, _
    newEntity, existingEntity, failure)
```

``` csharp
public static bool AssertPropertyNotChanged<T>(
    string propertyName,
    T newEntity,
    CommerceEntity existingEntity,
    out DataValidationFailure failure
)
where T : CommerceEntity
```

``` c++
public:
generic<typename T>
where T : CommerceEntity
static bool AssertPropertyNotChanged(
    String^ propertyName, 
    T newEntity, 
    CommerceEntity^ existingEntity, 
    [OutAttribute] DataValidationFailure^% failure
)
```

#### Type Parameters

  - T

#### Parameters

  - propertyName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - newEntity  
    Type: T  

<!-- end list -->

  - existingEntity  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - failure  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataValidationFailure](datavalidationfailure-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns whether the property has not been changed (tue) or changed (false).  

## See Also

#### Reference

[ReadOnlyAttribute Class](readonlyattribute-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


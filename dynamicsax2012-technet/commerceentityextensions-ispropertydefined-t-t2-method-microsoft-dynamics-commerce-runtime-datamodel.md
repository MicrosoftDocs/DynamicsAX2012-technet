---
title: CommerceEntityExtensions.IsPropertyDefined(T, T2) Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsPropertyDefined(T, T2) Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntityExtensions.IsPropertyDefined``2(``0,System.Linq.Expressions.Expression{System.Func{``0,``1}})
ms:mtpsurl: https://technet.microsoft.com/library/Dn998602(v=AX.60)
ms:contentKeyID: 65317033
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntityExtensions.IsPropertyDefined``2
dev_langs:
- CSharp
- C++
- VB
---

# IsPropertyDefined(T, T2) Method

Checks whether a property is defined in this entity or not.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Function IsPropertyDefined(Of T As CommerceEntity, T2) ( _
    value As T, _
    propertyLambda As Expression(Of Func(Of T, T2)) _
) As Boolean
'Usage
Dim value As T
Dim propertyLambda As Expression(Of Func(Of T, T2))
Dim returnValue As Boolean

returnValue = value.IsPropertyDefined(propertyLambda)
```

``` csharp
public static bool IsPropertyDefined<T, T2>(
    this T value,
    Expression<Func<T, T2>> propertyLambda
)
where T : CommerceEntity
```

``` c++
[ExtensionAttribute]
public:
generic<typename T, typename T2>
where T : CommerceEntity
static bool IsPropertyDefined(
    T value, 
    Expression<Func<T, T2>^>^ propertyLambda
)
```

#### Type Parameters

  - T

<!-- end list -->

  - T2

#### Parameters

  - value  
    Type: T  

<!-- end list -->

  - propertyLambda  
    Type: [System.Linq.Expressions.Expression](https://technet.microsoft.com/library/bb335710\(v=ax.60\))\<[Func](https://technet.microsoft.com/library/bb549151\(v=ax.60\))\<T, T2\>\>  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Whether the property is defined in this entity or not.  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type . When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[CommerceEntityExtensions Class](commerceentityextensions-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


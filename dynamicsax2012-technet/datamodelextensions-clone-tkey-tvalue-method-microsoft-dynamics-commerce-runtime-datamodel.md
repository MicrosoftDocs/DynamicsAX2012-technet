---
title: DataModelExtensions.Clone(TKey, TValue) Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Clone(TKey, TValue) Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.DataModelExtensions.Clone``2(System.Collections.Generic.Dictionary{``0,``1})
ms:mtpsurl: https://technet.microsoft.com/library/Dn966283(v=AX.60)
ms:contentKeyID: 65315471
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DataModelExtensions.Clone``2
dev_langs:
- CSharp
- C++
- VB
---

# Clone(TKey, TValue) Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Clone(Of TKey, TValue As {New, CommerceEntity}) ( _
    originalDictionary As Dictionary(Of TKey, TValue) _
) As Dictionary(Of TKey, TValue)
'Usage
Dim originalDictionary As Dictionary(Of TKey, TValue)
Dim returnValue As Dictionary(Of TKey, TValue)

returnValue = originalDictionary.Clone()
```

``` csharp
public static Dictionary<TKey, TValue> Clone<TKey, TValue>(
    this Dictionary<TKey, TValue> originalDictionary
)
where TValue : new(), CommerceEntity
```

``` c++
[ExtensionAttribute]
public:
generic<typename TKey, typename TValue>
where TValue : gcnew(), CommerceEntity
static Dictionary<TKey, TValue>^ Clone(
    Dictionary<TKey, TValue>^ originalDictionary
)
```

#### Type Parameters

  - TKey

<!-- end list -->

  - TValue

#### Parameters

  - originalDictionary  
    Type: [System.Collections.Generic.Dictionary](https://technet.microsoft.com/library/xfhwa508\(v=ax.60\))\<TKey, TValue\>  

#### Return Value

Type: [System.Collections.Generic.Dictionary](https://technet.microsoft.com/library/xfhwa508\(v=ax.60\))\<TKey, TValue\>  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [Dictionary](https://technet.microsoft.com/library/xfhwa508\(v=ax.60\))\<TKey, TValue\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[DataModelExtensions Class](datamodelextensions-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


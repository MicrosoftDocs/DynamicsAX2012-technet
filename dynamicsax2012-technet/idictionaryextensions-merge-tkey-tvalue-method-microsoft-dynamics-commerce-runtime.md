---
title: IDictionaryExtensions.Merge(TKey, TValue) Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: Merge(TKey, TValue) Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.IDictionaryExtensions.Merge``2(System.Collections.Generic.IDictionary{``0,``1},System.Collections.Generic.IEnumerable{System.Collections.Generic.KeyValuePair{``0,``1}})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn718436(v=AX.60)
ms:contentKeyID: 62213559
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.IDictionaryExtensions.Merge``2
dev_langs:
- CSharp
- C++
- VB
---

# Merge(TKey, TValue) Method

Merges collection collection to current dictionary.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Sub Merge(Of TKey, TValue) ( _
    dictionary As IDictionary(Of TKey, TValue), _
    collection As IEnumerable(Of KeyValuePair(Of TKey, TValue)) _
)
'Usage
Dim dictionary As IDictionary(Of TKey, TValue)
Dim collection As IEnumerable(Of KeyValuePair(Of TKey, TValue))

dictionary.Merge(collection)
```

``` csharp
public static void Merge<TKey, TValue>(
    this IDictionary<TKey, TValue> dictionary,
    IEnumerable<KeyValuePair<TKey, TValue>> collection
)
```

``` c++
[ExtensionAttribute]
public:
generic<typename TKey, typename TValue>
static void Merge(
    IDictionary<TKey, TValue>^ dictionary, 
    IEnumerable<KeyValuePair<TKey, TValue>>^ collection
)
```

#### Type Parameters

  - TKey

<!-- end list -->

  - TValue

#### Parameters

  - dictionary  
    Type: [System.Collections.Generic.IDictionary](https://technet.microsoft.com/en-us/library/s4ys34ea\(v=ax.60\))\<TKey, TValue\>  

<!-- end list -->

  - collection  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[KeyValuePair](https://technet.microsoft.com/en-us/library/5tbh8a42\(v=ax.60\))\<TKey, TValue\>\>  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IDictionary](https://technet.microsoft.com/en-us/library/s4ys34ea\(v=ax.60\))\<TKey, TValue\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[IDictionaryExtensions Class](idictionaryextensions-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)


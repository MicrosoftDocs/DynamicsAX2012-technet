---
title: DataStorePolicy.HasLogic Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: HasLogic Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.DataStorePolicy.HasLogic
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.datastorepolicy.haslogic(v=AX.60)
ms:contentKeyID: 62212213
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DataStorePolicy.HasLogic
dev_langs:
- CSharp
- C++
- VB
---

# HasLogic Property

Gets a value indicating whether the data store embeds logic/can execute code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property HasLogic As Boolean
    Get
'Usage
Dim instance As DataStorePolicy
Dim value As Boolean

value = instance.HasLogic
```

``` csharp
public bool HasLogic { get; }
```

``` c++
public:
property bool HasLogic {
    bool get ();
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)).  

## Remarks

This serves mainly to differentiate a database-type store from static data collections.

## See Also

#### Reference

[DataStorePolicy Class](datastorepolicy-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


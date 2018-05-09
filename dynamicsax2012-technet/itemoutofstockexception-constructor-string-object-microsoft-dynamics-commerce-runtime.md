---
title: ItemOutOfStockException Constructor (String, Object ) (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: ItemOutOfStockException Constructor (String, Object )
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.ItemOutOfStockException.#ctor(System.String,System.Object[])
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.itemoutofstockexception.itemoutofstockexception(v=AX.60)
ms:contentKeyID: 49842386
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ItemOutOfStockException Constructor (String, Object )

Initializes an instance of the [DataValidationException](datavalidationexception-class-microsoft-dynamics-commerce-runtime.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    message As String, _
    ParamArray args As Object() _
)
'Usage
Dim message As String
Dim args As Object()

Dim instance As New ItemOutOfStockException(message, _
    args)
```

``` csharp
public ItemOutOfStockException(
    string message,
    params Object[] args
)
```

``` c++
public:
ItemOutOfStockException(
    String^ message, 
    ... array<Object^>^ args
)
```

#### Parameters

  - message  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - args  
    Type: [System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))\[\]  

## See Also

#### Reference

[ItemOutOfStockException Class](itemoutofstockexception-class-microsoft-dynamics-commerce-runtime.md)

[ItemOutOfStockException Overload](itemoutofstockexception-constructor-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)


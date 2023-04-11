---
title: ItemOutOfStockException Class (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: ItemOutOfStockException Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.ItemOutOfStockException
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.itemoutofstockexception(v=AX.60)
ms:contentKeyID: 49847861
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ItemOutOfStockException
dev_langs:
- CSharp
- C++
- VB
---

# ItemOutOfStockException Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Represents the exception for item out of stock error which is thrown on item reservation when there are not enough items in stock to be reserved.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class ItemOutOfStockException _
    Inherits DataValidationException
'Usage
Dim instance As ItemOutOfStockException
```

``` csharp
public sealed class ItemOutOfStockException : DataValidationException
```

``` c++
public ref class ItemOutOfStockException sealed : public DataValidationException
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [System.Exception](https://technet.microsoft.com/library/c18k6c59\(v=ax.60\))  
    [Microsoft.Dynamics.Commerce.Runtime.CommerceRuntimeException](commerceruntimeexception-class-microsoft-dynamics-commerce-runtime.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataValidationException](datavalidationexception-class-microsoft-dynamics-commerce-runtime.md)  
        Microsoft.Dynamics.Commerce.Runtime.ItemOutOfStockException  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)


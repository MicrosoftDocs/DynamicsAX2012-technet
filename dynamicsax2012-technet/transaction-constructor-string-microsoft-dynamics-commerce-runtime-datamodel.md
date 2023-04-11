---
title: Transaction Constructor (String) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Transaction Constructor (String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.Transaction.#ctor(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.transaction.transaction(v=AX.60)
ms:contentKeyID: 62211163
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Transaction Constructor (String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [Transaction](transaction-class-microsoft-dynamics-commerce-runtime-datamodel.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Protected Sub New ( _
    entityName As String _
)
'Usage
Dim entityName As String

Dim instance As New Transaction(entityName)
```

``` csharp
protected Transaction(
    string entityName
)
```

``` c++
protected:
Transaction(
    String^ entityName
)
```

#### Parameters

  - entityName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[Transaction Class](transaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Transaction Overload](transaction-constructor-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


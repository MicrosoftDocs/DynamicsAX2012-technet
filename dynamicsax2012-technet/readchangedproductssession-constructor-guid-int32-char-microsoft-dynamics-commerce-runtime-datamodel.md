---
title: ReadChangedProductsSession Constructor (Guid, Int32, Char ) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReadChangedProductsSession Constructor (Guid, Int32, Char )
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReadChangedProductsSession.#ctor(System.Guid,System.Int32,System.Char[])
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.readchangedproductssession.readchangedproductssession(v=AX.60)
ms:contentKeyID: 62203201
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ReadChangedProductsSession Constructor (Guid, Int32, Char )[AX 2012]

Initializes a new instance of the [ReadChangedProductsSession](readchangedproductssession-class-microsoft-dynamics-commerce-runtime-datamodel.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    id As Guid, _
    totalNumberOfProducts As Integer, _
    nextSynchronizationToken As Char() _
)
'Usage
Dim id As Guid
Dim totalNumberOfProducts As Integer
Dim nextSynchronizationToken As Char()

Dim instance As New ReadChangedProductsSession(id, totalNumberOfProducts, _
    nextSynchronizationToken)
```

``` csharp
public ReadChangedProductsSession(
    Guid id,
    int totalNumberOfProducts,
    char[] nextSynchronizationToken
)
```

``` c++
public:
ReadChangedProductsSession(
    Guid id, 
    int totalNumberOfProducts, 
    array<wchar_t>^ nextSynchronizationToken
)
```

#### Parameters

  - id  
    Type: [System.Guid](https://technet.microsoft.com/en-us/library/cey1zx63\(v=ax.60\))  

<!-- end list -->

  - totalNumberOfProducts  
    Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  

<!-- end list -->

  - nextSynchronizationToken  
    Type: [System.Char](https://technet.microsoft.com/en-us/library/k493b04s\(v=ax.60\))\[\]  

## See Also

#### Reference

[ReadChangedProductsSession Class](readchangedproductssession-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[ReadChangedProductsSession Overload](readchangedproductssession-constructor-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


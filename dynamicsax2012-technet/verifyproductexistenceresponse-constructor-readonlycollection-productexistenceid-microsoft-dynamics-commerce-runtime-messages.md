---
title: VerifyProductExistenceResponse Constructor (ReadOnlyCollection(ProductExistenceId)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: VerifyProductExistenceResponse Constructor (ReadOnlyCollection(ProductExistenceId))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.VerifyProductExistenceResponse.#ctor(System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductExistenceId})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.verifyproductexistenceresponse.verifyproductexistenceresponse(v=AX.60)
ms:contentKeyID: 62213656
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# VerifyProductExistenceResponse Constructor (ReadOnlyCollection(ProductExistenceId))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [VerifyProductExistenceResponse](verifyproductexistenceresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    ids As ReadOnlyCollection(Of ProductExistenceId) _
)
'Usage
Dim ids As ReadOnlyCollection(Of ProductExistenceId)

Dim instance As New VerifyProductExistenceResponse(ids)
```

``` csharp
public VerifyProductExistenceResponse(
    ReadOnlyCollection<ProductExistenceId> ids
)
```

``` c++
public:
VerifyProductExistenceResponse(
    ReadOnlyCollection<ProductExistenceId^>^ ids
)
```

#### Parameters

  - ids  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductExistenceId](productexistenceid-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[VerifyProductExistenceResponse Class](verifyproductexistenceresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[VerifyProductExistenceResponse Overload](verifyproductexistenceresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


---
title: GetStoreOperationResponse Constructor (IEnumerable(NonSalesTransaction)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetStoreOperationResponse Constructor (IEnumerable(NonSalesTransaction))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoreOperationResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.NonSalesTransaction})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getstoreoperationresponse.getstoreoperationresponse(v=AX.60)
ms:contentKeyID: 62211305
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetStoreOperationResponse Constructor (IEnumerable(NonSalesTransaction))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetStoreOperationResponse](getstoreoperationresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    nonSalesTenderOperations As IEnumerable(Of NonSalesTransaction) _
)
'Usage
Dim nonSalesTenderOperations As IEnumerable(Of NonSalesTransaction)

Dim instance As New GetStoreOperationResponse(nonSalesTenderOperations)
```

``` csharp
public GetStoreOperationResponse(
    IEnumerable<NonSalesTransaction> nonSalesTenderOperations
)
```

``` c++
public:
GetStoreOperationResponse(
    IEnumerable<NonSalesTransaction^>^ nonSalesTenderOperations
)
```

#### Parameters

  - nonSalesTenderOperations  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[NonSalesTransaction](nonsalestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetStoreOperationResponse Class](getstoreoperationresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetStoreOperationResponse Overload](getstoreoperationresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


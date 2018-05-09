---
title: DeleteCartDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: DeleteCartDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.DeleteCartDataRequest.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.deletecartdatarequest.deletecartdatarequest(v=AX.60)
ms:contentKeyID: 65322329
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.DeleteCartDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# DeleteCartDataRequest Constructor

Initializes a new instance of the [DeleteCartDataRequest](deletecartdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    salesTransactions As IEnumerable(Of SalesTransaction) _
)
'Usage
Dim salesTransactions As IEnumerable(Of SalesTransaction)

Dim instance As New DeleteCartDataRequest(salesTransactions)
```

``` csharp
public DeleteCartDataRequest(
    IEnumerable<SalesTransaction> salesTransactions
)
```

``` c++
public:
DeleteCartDataRequest(
    IEnumerable<SalesTransaction^>^ salesTransactions
)
```

#### Parameters

  - salesTransactions  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[DeleteCartDataRequest Class](deletecartdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


---
title: SaveCartDataRequest Constructor (IEnumerable(SalesTransaction), Boolean) (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: SaveCartDataRequest Constructor (IEnumerable(SalesTransaction), Boolean)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SaveCartDataRequest.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction},System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.savecartdatarequest.savecartdatarequest(v=AX.60)
ms:contentKeyID: 65322354
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SaveCartDataRequest Constructor (IEnumerable(SalesTransaction), Boolean)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [SaveCartDataRequest](savecartdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    salesTransactions As IEnumerable(Of SalesTransaction), _
    ignoreRowVersionCheck As Boolean _
)
'Usage
Dim salesTransactions As IEnumerable(Of SalesTransaction)
Dim ignoreRowVersionCheck As Boolean

Dim instance As New SaveCartDataRequest(salesTransactions, _
    ignoreRowVersionCheck)
```

``` csharp
public SaveCartDataRequest(
    IEnumerable<SalesTransaction> salesTransactions,
    bool ignoreRowVersionCheck
)
```

``` c++
public:
SaveCartDataRequest(
    IEnumerable<SalesTransaction^>^ salesTransactions, 
    bool ignoreRowVersionCheck
)
```

#### Parameters

  - salesTransactions  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - ignoreRowVersionCheck  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[SaveCartDataRequest Class](savecartdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[SaveCartDataRequest Overload](savecartdatarequest-constructor-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


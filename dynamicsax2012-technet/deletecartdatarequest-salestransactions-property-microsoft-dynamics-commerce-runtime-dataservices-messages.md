---
title: DeleteCartDataRequest.SalesTransactions Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: SalesTransactions Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.DeleteCartDataRequest.SalesTransactions
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.deletecartdatarequest.salestransactions(v=AX.60)
ms:contentKeyID: 65323084
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.DeleteCartDataRequest.SalesTransactions
dev_langs:
- CSharp
- C++
- VB
---

# SalesTransactions Property

Gets the sales transaction to be saved.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property SalesTransactions As IEnumerable(Of SalesTransaction)
    Get
    Private Set
'Usage
Dim instance As DeleteCartDataRequest
Dim value As IEnumerable(Of SalesTransaction)

value = instance.SalesTransactions
```

``` csharp
public IEnumerable<SalesTransaction> SalesTransactions { get; private set; }
```

``` c++
public:
property IEnumerable<SalesTransaction^>^ SalesTransactions {
    IEnumerable<SalesTransaction^>^ get ();
    private: void set (IEnumerable<SalesTransaction^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[DeleteCartDataRequest Class](deletecartdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


---
title: SaveSalesTransactionDataRequest.SalesTransaction Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: SalesTransaction Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SaveSalesTransactionDataRequest.SalesTransaction
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.savesalestransactiondatarequest.salestransaction(v=AX.60)
ms:contentKeyID: 65322168
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SaveSalesTransactionDataRequest.SalesTransaction
dev_langs:
- CSharp
- C++
- VB
---

# SalesTransaction Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the sales transaction to be saved.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property SalesTransaction As SalesTransaction
    Get
    Private Set
'Usage
Dim instance As SaveSalesTransactionDataRequest
Dim value As SalesTransaction

value = instance.SalesTransaction
```

``` csharp
public SalesTransaction SalesTransaction { get; private set; }
```

``` c++
public:
property SalesTransaction^ SalesTransaction {
    SalesTransaction^ get ();
    private: void set (SalesTransaction^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[SaveSalesTransactionDataRequest Class](savesalestransactiondatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


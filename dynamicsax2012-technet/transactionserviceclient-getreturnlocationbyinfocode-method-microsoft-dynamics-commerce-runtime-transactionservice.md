---
title: TransactionServiceClient.GetReturnLocationByInfoCode Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: GetReturnLocationByInfoCode Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetReturnLocationByInfoCode(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction,Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.getreturnlocationbyinfocode(v=AX.60)
ms:contentKeyID: 65321822
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetReturnLocationByInfoCode
dev_langs:
- CSharp
- C++
- VB
---

# GetReturnLocationByInfoCode Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Function GetReturnLocationByInfoCode ( _
    transaction As SalesTransaction, _
    line As SalesLine _
) As ReadOnlyCollection(Of Object)
'Usage
Dim instance As TransactionServiceClient
Dim transaction As SalesTransaction
Dim line As SalesLine
Dim returnValue As ReadOnlyCollection(Of Object)

returnValue = instance.GetReturnLocationByInfoCode(transaction, _
    line)
```

``` csharp
public ReadOnlyCollection<Object> GetReturnLocationByInfoCode(
    SalesTransaction transaction,
    SalesLine line
)
```

``` c++
public:
ReadOnlyCollection<Object^>^ GetReturnLocationByInfoCode(
    SalesTransaction^ transaction, 
    SalesLine^ line
)
```

#### Parameters

  - transaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - line  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))\>  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)


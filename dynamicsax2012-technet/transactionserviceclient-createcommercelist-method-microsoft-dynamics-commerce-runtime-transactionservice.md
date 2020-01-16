---
title: TransactionServiceClient.CreateCommerceList Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: CreateCommerceList Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.CreateCommerceList(Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceList)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.createcommercelist(v=AX.60)
ms:contentKeyID: 62214315
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.CreateCommerceList
dev_langs:
- CSharp
- C++
- VB
---

# CreateCommerceList Method

Create a commerce list.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Function CreateCommerceList ( _
    commerceList As CommerceList _
) As CommerceList
'Usage
Dim instance As TransactionServiceClient
Dim commerceList As CommerceList
Dim returnValue As CommerceList

returnValue = instance.CreateCommerceList(commerceList)
```

``` csharp
public CommerceList CreateCommerceList(
    CommerceList commerceList
)
```

``` c++
public:
CommerceList^ CreateCommerceList(
    CommerceList^ commerceList
)
```

#### Parameters

  - commerceList  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceList](commercelist-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceList](commercelist-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns the commerce list object with a record id.  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)


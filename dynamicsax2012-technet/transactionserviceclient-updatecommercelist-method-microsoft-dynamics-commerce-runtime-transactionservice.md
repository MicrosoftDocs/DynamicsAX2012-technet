---
title: TransactionServiceClient.UpdateCommerceList Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: UpdateCommerceList Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.UpdateCommerceList(Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceList)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.updatecommercelist(v=AX.60)
ms:contentKeyID: 62202689
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.UpdateCommerceList
dev_langs:
- CSharp
- C++
- VB
---

# UpdateCommerceList Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Update a commerce list.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Function UpdateCommerceList ( _
    commerceList As CommerceList _
) As CommerceList
'Usage
Dim instance As TransactionServiceClient
Dim commerceList As CommerceList
Dim returnValue As CommerceList

returnValue = instance.UpdateCommerceList(commerceList)
```

``` csharp
public CommerceList UpdateCommerceList(
    CommerceList commerceList
)
```

``` c++
public:
CommerceList^ UpdateCommerceList(
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


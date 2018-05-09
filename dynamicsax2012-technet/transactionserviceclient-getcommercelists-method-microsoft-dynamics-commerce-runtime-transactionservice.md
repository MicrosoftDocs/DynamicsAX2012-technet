---
title: TransactionServiceClient.GetCommerceLists Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: GetCommerceLists Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetCommerceLists(System.String,System.String,System.Boolean,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.getcommercelists(v=AX.60)
ms:contentKeyID: 62211354
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetCommerceLists
dev_langs:
- CSharp
- C++
- VB
---

# GetCommerceLists Method

Retrieves the commerce lists from AX.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Function GetCommerceLists ( _
    commerceListId As String, _
    customerId As String, _
    favoriteFilter As Boolean, _
    publicFilter As Boolean _
) As ReadOnlyCollection(Of CommerceList)
'Usage
Dim instance As TransactionServiceClient
Dim commerceListId As String
Dim customerId As String
Dim favoriteFilter As Boolean
Dim publicFilter As Boolean
Dim returnValue As ReadOnlyCollection(Of CommerceList)

returnValue = instance.GetCommerceLists(commerceListId, _
    customerId, favoriteFilter, publicFilter)
```

``` csharp
public ReadOnlyCollection<CommerceList> GetCommerceLists(
    string commerceListId,
    string customerId,
    bool favoriteFilter,
    bool publicFilter
)
```

``` c++
public:
ReadOnlyCollection<CommerceList^>^ GetCommerceLists(
    String^ commerceListId, 
    String^ customerId, 
    bool favoriteFilter, 
    bool publicFilter
)
```

#### Parameters

  - commerceListId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - customerId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - favoriteFilter  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - publicFilter  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[CommerceList](commercelist-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns the commerce lists from AX.  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)


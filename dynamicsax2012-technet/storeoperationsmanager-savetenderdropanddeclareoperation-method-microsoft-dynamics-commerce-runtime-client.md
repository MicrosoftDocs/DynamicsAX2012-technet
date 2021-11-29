---
title: StoreOperationsManager.SaveTenderDropAndDeclareOperation Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: SaveTenderDropAndDeclareOperation Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.StoreOperationsManager.SaveTenderDropAndDeclareOperation(Microsoft.Dynamics.Commerce.Runtime.DataModel.DropAndDeclareTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.storeoperationsmanager.savetenderdropanddeclareoperation(v=AX.60)
ms:contentKeyID: 62205178
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.StoreOperationsManager.SaveTenderDropAndDeclareOperation
dev_langs:
- CSharp
- C++
- VB
---

# SaveTenderDropAndDeclareOperation Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Saves the tender drop and declare operation transactions.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function SaveTenderDropAndDeclareOperation ( _
    transaction As DropAndDeclareTransaction _
) As DropAndDeclareTransaction
'Usage
Dim instance As StoreOperationsManager
Dim transaction As DropAndDeclareTransaction
Dim returnValue As DropAndDeclareTransaction

returnValue = instance.SaveTenderDropAndDeclareOperation(transaction)
```

``` csharp
public DropAndDeclareTransaction SaveTenderDropAndDeclareOperation(
    DropAndDeclareTransaction transaction
)
```

``` c++
public:
DropAndDeclareTransaction^ SaveTenderDropAndDeclareOperation(
    DropAndDeclareTransaction^ transaction
)
```

#### Parameters

  - transaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DropAndDeclareTransaction](dropanddeclaretransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DropAndDeclareTransaction](dropanddeclaretransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns tender drop and declare object.  

## See Also

#### Reference

[StoreOperationsManager Class](storeoperationsmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)


---
title: StoreOperationsManager.SaveNonSaleTenderOperation Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: SaveNonSaleTenderOperation Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.StoreOperationsManager.SaveNonSaleTenderOperation(Microsoft.Dynamics.Commerce.Runtime.DataModel.NonSalesTransaction)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.storeoperationsmanager.savenonsaletenderoperation(v=AX.60)
ms:contentKeyID: 62208553
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.StoreOperationsManager.SaveNonSaleTenderOperation
dev_langs:
- CSharp
- C++
- VB
---

# SaveNonSaleTenderOperation Method

Saves the tender drop and declare operation transactions.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function SaveNonSaleTenderOperation ( _
    transaction As NonSalesTransaction _
) As NonSalesTransaction
'Usage
Dim instance As StoreOperationsManager
Dim transaction As NonSalesTransaction
Dim returnValue As NonSalesTransaction

returnValue = instance.SaveNonSaleTenderOperation(transaction)
```

``` csharp
public NonSalesTransaction SaveNonSaleTenderOperation(
    NonSalesTransaction transaction
)
```

``` c++
public:
NonSalesTransaction^ SaveNonSaleTenderOperation(
    NonSalesTransaction^ transaction
)
```

#### Parameters

  - transaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.NonSalesTransaction](nonsalestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.NonSalesTransaction](nonsalestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns non sale tender operation object.  

## See Also

#### Reference

[StoreOperationsManager Class](storeoperationsmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)


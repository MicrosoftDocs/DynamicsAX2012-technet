---
title: NonSaleTenderOperationDataManager.GetCurrentShiftNonSaleOperations Method (NonSalesTransaction) (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: GetCurrentShiftNonSaleOperations Method (NonSalesTransaction)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.NonSaleTenderOperationDataManager.GetCurrentShiftNonSaleOperations(Microsoft.Dynamics.Commerce.Runtime.DataModel.NonSalesTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.nonsaletenderoperationdatamanager.getcurrentshiftnonsaleoperations(v=AX.60)
ms:contentKeyID: 62208902
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetCurrentShiftNonSaleOperations Method (NonSalesTransaction)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the list of transactions for the current shift.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetCurrentShiftNonSaleOperations ( _
    transaction As NonSalesTransaction _
) As ReadOnlyCollection(Of NonSalesTransaction)
'Usage
Dim instance As NonSaleTenderOperationDataManager
Dim transaction As NonSalesTransaction
Dim returnValue As ReadOnlyCollection(Of NonSalesTransaction)

returnValue = instance.GetCurrentShiftNonSaleOperations(transaction)
```

``` csharp
public ReadOnlyCollection<NonSalesTransaction> GetCurrentShiftNonSaleOperations(
    NonSalesTransaction transaction
)
```

``` c++
public:
ReadOnlyCollection<NonSalesTransaction^>^ GetCurrentShiftNonSaleOperations(
    NonSalesTransaction^ transaction
)
```

#### Parameters

  - transaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.NonSalesTransaction](nonsalestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[NonSalesTransaction](nonsalestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Collection of non-sale tender operation.  

## See Also

#### Reference

[NonSaleTenderOperationDataManager Class](nonsaletenderoperationdatamanager-class-microsoft-dynamics-commerce-runtime.md)

[GetCurrentShiftNonSaleOperations Overload](nonsaletenderoperationdatamanager-getcurrentshiftnonsaleoperations-method-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)


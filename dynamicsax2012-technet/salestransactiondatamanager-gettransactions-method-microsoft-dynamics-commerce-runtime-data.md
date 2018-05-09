---
title: SalesTransactionDataManager.GetTransactions Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetTransactions Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.SalesTransactionDataManager.GetTransactions(Microsoft.Dynamics.Commerce.Runtime.ParameterSet,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.salestransactiondatamanager.gettransactions(v=AX.60)
ms:contentKeyID: 65317480
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.SalesTransactionDataManager.GetTransactions
dev_langs:
- CSharp
- C++
- VB
---

# GetTransactions Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetTransactions ( _
    parameters As ParameterSet, _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of SalesTransaction)
'Usage
Dim instance As SalesTransactionDataManager
Dim parameters As ParameterSet
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of SalesTransaction)

returnValue = instance.GetTransactions(parameters, _
    settings)
```

``` csharp
public ReadOnlyCollection<SalesTransaction> GetTransactions(
    ParameterSet parameters,
    QueryResultSettings settings
)
```

``` c++
public:
ReadOnlyCollection<SalesTransaction^>^ GetTransactions(
    ParameterSet^ parameters, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - parameters  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ParameterSet](parameterset-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[SalesTransactionDataManager Class](salestransactiondatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


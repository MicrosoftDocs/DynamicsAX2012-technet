---
title: TenderDropAndDeclareDataManager.GetTransactionTenders Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: GetTransactionTenders Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TenderDropAndDeclareDataManager.GetTransactionTenders(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.tenderdropanddeclaredatamanager.gettransactiontenders(v=AX.60)
ms:contentKeyID: 65320403
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TenderDropAndDeclareDataManager.GetTransactionTenders
dev_langs:
- CSharp
- C++
- VB
---

# GetTransactionTenders Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetTransactionTenders ( _
    transactionId As String, _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of TenderDetail)
'Usage
Dim instance As TenderDropAndDeclareDataManager
Dim transactionId As String
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of TenderDetail)

returnValue = instance.GetTransactionTenders(transactionId, _
    settings)
```

``` csharp
public ReadOnlyCollection<TenderDetail> GetTransactionTenders(
    string transactionId,
    QueryResultSettings settings
)
```

``` c++
public:
ReadOnlyCollection<TenderDetail^>^ GetTransactionTenders(
    String^ transactionId, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - transactionId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[TenderDetail](tenderdetail-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[TenderDropAndDeclareDataManager Class](tenderdropanddeclaredatamanager-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)


---
title: SalesOrderDataManager.GetTenderLinesForSalesOrder Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetTenderLinesForSalesOrder Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.SalesOrderDataManager.GetTenderLinesForSalesOrder(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.salesorderdatamanager.gettenderlinesforsalesorder(v=AX.60)
ms:contentKeyID: 65318808
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.SalesOrderDataManager.GetTenderLinesForSalesOrder
dev_langs:
- CSharp
- C++
- VB
---

# GetTenderLinesForSalesOrder Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetTenderLinesForSalesOrder ( _
    transactionId As String, _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of TenderLine)
'Usage
Dim instance As SalesOrderDataManager
Dim transactionId As String
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of TenderLine)

returnValue = instance.GetTenderLinesForSalesOrder(transactionId, _
    settings)
```

``` csharp
public ReadOnlyCollection<TenderLine> GetTenderLinesForSalesOrder(
    string transactionId,
    QueryResultSettings settings
)
```

``` c++
public:
ReadOnlyCollection<TenderLine^>^ GetTenderLinesForSalesOrder(
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

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[TenderLine](tenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[SalesOrderDataManager Class](salesorderdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


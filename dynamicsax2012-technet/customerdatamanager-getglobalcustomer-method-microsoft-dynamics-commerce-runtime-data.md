---
title: CustomerDataManager.GetGlobalCustomer Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetGlobalCustomer Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.CustomerDataManager.GetGlobalCustomer(System.String,Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.customerdatamanager.getglobalcustomer(v=AX.60)
ms:contentKeyID: 62208616
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.CustomerDataManager.GetGlobalCustomer
dev_langs:
- CSharp
- C++
- VB
---

# GetGlobalCustomer Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the global customer.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetGlobalCustomer ( _
    partyNumber As String, _
    columns As ColumnSet _
) As GlobalCustomer
'Usage
Dim instance As CustomerDataManager
Dim partyNumber As String
Dim columns As ColumnSet
Dim returnValue As GlobalCustomer

returnValue = instance.GetGlobalCustomer(partyNumber, _
    columns)
```

``` csharp
public GlobalCustomer GetGlobalCustomer(
    string partyNumber,
    ColumnSet columns
)
```

``` c++
public:
GlobalCustomer^ GetGlobalCustomer(
    String^ partyNumber, 
    ColumnSet^ columns
)
```

#### Parameters

  - partyNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.GlobalCustomer](globalcustomer-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
A single global customer.  

## See Also

#### Reference

[CustomerDataManager Class](customerdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


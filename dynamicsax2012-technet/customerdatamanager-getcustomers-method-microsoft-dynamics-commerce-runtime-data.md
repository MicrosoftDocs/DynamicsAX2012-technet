---
title: CustomerDataManager.GetCustomers Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetCustomers Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.CustomerDataManager.GetCustomers(System.Int64,System.String,System.Int64,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.customerdatamanager.getcustomers(v=AX.60)
ms:contentKeyID: 65315746
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.CustomerDataManager.GetCustomers
dev_langs:
- CSharp
- C++
- VB
---

# GetCustomers Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetCustomers ( _
    recordId As Long, _
    accountNumber As String, _
    dirPartyRecId As Long, _
    partyNumber As String, _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of Customer)
'Usage
Dim instance As CustomerDataManager
Dim recordId As Long
Dim accountNumber As String
Dim dirPartyRecId As Long
Dim partyNumber As String
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of Customer)

returnValue = instance.GetCustomers(recordId, _
    accountNumber, dirPartyRecId, partyNumber, _
    settings)
```

``` csharp
public ReadOnlyCollection<Customer> GetCustomers(
    long recordId,
    string accountNumber,
    long dirPartyRecId,
    string partyNumber,
    QueryResultSettings settings
)
```

``` c++
public:
ReadOnlyCollection<Customer^>^ GetCustomers(
    long long recordId, 
    String^ accountNumber, 
    long long dirPartyRecId, 
    String^ partyNumber, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - recordId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - accountNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - dirPartyRecId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - partyNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Customer](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[CustomerDataManager Class](customerdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


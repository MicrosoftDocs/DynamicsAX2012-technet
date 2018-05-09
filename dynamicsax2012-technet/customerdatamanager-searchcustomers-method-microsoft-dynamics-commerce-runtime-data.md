---
title: CustomerDataManager.SearchCustomers Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: SearchCustomers Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.CustomerDataManager.SearchCustomers(System.String,System.Boolean,System.Int64,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.customerdatamanager.searchcustomers(v=AX.60)
ms:contentKeyID: 65321966
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.CustomerDataManager.SearchCustomers
dev_langs:
- CSharp
- C++
- VB
---

# SearchCustomers Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function SearchCustomers ( _
    keyword As String, _
    onlyCurrentCompany As Boolean, _
    channelId As Long, _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of GlobalCustomer)
'Usage
Dim instance As CustomerDataManager
Dim keyword As String
Dim onlyCurrentCompany As Boolean
Dim channelId As Long
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of GlobalCustomer)

returnValue = instance.SearchCustomers(keyword, _
    onlyCurrentCompany, channelId, settings)
```

``` csharp
public ReadOnlyCollection<GlobalCustomer> SearchCustomers(
    string keyword,
    bool onlyCurrentCompany,
    long channelId,
    QueryResultSettings settings
)
```

``` c++
public:
ReadOnlyCollection<GlobalCustomer^>^ SearchCustomers(
    String^ keyword, 
    bool onlyCurrentCompany, 
    long long channelId, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - keyword  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - onlyCurrentCompany  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[GlobalCustomer](globalcustomer-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[CustomerDataManager Class](customerdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


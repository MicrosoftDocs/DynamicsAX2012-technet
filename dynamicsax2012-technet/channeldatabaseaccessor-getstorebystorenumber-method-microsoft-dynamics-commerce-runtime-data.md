---
title: ChannelDatabaseAccessor.GetStoreByStoreNumber Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetStoreByStoreNumber Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDatabaseAccessor.GetStoreByStoreNumber(System.Collections.Generic.IEnumerable{System.String},Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.channeldatabaseaccessor.getstorebystorenumber(v=AX.60)
ms:contentKeyID: 65322844
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDatabaseAccessor.GetStoreByStoreNumber
dev_langs:
- CSharp
- C++
- VB
---

# GetStoreByStoreNumber Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetStoreByStoreNumber ( _
    storeNumbers As IEnumerable(Of String), _
    settings As QueryResultSettings _
) As PagedResult(Of OrgUnit)
'Usage
Dim instance As ChannelDatabaseAccessor
Dim storeNumbers As IEnumerable(Of String)
Dim settings As QueryResultSettings
Dim returnValue As PagedResult(Of OrgUnit)

returnValue = instance.GetStoreByStoreNumber(storeNumbers, _
    settings)
```

``` csharp
public PagedResult<OrgUnit> GetStoreByStoreNumber(
    IEnumerable<string> storeNumbers,
    QueryResultSettings settings
)
```

``` c++
public:
PagedResult<OrgUnit^>^ GetStoreByStoreNumber(
    IEnumerable<String^>^ storeNumbers, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - storeNumbers  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[OrgUnit](orgunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ChannelDatabaseAccessor Class](channeldatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


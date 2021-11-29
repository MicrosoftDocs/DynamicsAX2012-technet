---
title: ChannelDataManager.GetDownloadingDataSet Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetDownloadingDataSet Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDataManager.GetDownloadingDataSet(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.channeldatamanager.getdownloadingdataset(v=AX.60)
ms:contentKeyID: 65321974
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDataManager.GetDownloadingDataSet
dev_langs:
- CSharp
- C++
- VB
---

# GetDownloadingDataSet Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetDownloadingDataSet ( _
    dataGroupName As String, _
    settings As QueryResultSettings _
) As DataSet
'Usage
Dim instance As ChannelDataManager
Dim dataGroupName As String
Dim settings As QueryResultSettings
Dim returnValue As DataSet

returnValue = instance.GetDownloadingDataSet(dataGroupName, _
    settings)
```

``` csharp
public DataSet GetDownloadingDataSet(
    string dataGroupName,
    QueryResultSettings settings
)
```

``` c++
public:
DataSet^ GetDownloadingDataSet(
    String^ dataGroupName, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - dataGroupName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataSet](dataset-class-microsoft-dynamics-commerce-runtime-data-types.md)  

## See Also

#### Reference

[ChannelDataManager Class](channeldatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)


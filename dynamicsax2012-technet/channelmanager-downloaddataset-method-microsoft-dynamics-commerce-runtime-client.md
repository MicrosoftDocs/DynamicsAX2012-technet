---
title: ChannelManager.DownloadDataSet Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: DownloadDataSet Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.DownloadDataSet(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.channelmanager.downloaddataset(v=AX.60)
ms:contentKeyID: 65322754
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.DownloadDataSet
dev_langs:
- CSharp
- C++
- VB
---

# DownloadDataSet Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function DownloadDataSet ( _
    dataGroupName As String, _
    settings As QueryResultSettings _
) As DataSet
'Usage
Dim instance As ChannelManager
Dim dataGroupName As String
Dim settings As QueryResultSettings
Dim returnValue As DataSet

returnValue = instance.DownloadDataSet(dataGroupName, _
    settings)
```

``` csharp
public DataSet DownloadDataSet(
    string dataGroupName,
    QueryResultSettings settings
)
```

``` c++
public:
DataSet^ DownloadDataSet(
    String^ dataGroupName, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - dataGroupName  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataSet](dataset-class-microsoft-dynamics-commerce-runtime-data-types.md)  

## See Also

#### Reference

[ChannelManager Class](channelmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)


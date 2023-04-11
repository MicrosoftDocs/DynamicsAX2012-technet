---
title: DownloadDataSetResponse.DataSet Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: DataSet Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.DownloadDataSetResponse.DataSet
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.downloaddatasetresponse.dataset(v=AX.60)
ms:contentKeyID: 62212181
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.DownloadDataSetResponse.DataSet
dev_langs:
- CSharp
- C++
- VB
---

# DataSet Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the channel tender types.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DataSet As DataSet
    Get
    Private Set
'Usage
Dim instance As DownloadDataSetResponse
Dim value As DataSet

value = instance.DataSet
```

``` csharp
[DataMemberAttribute]
public DataSet DataSet { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property DataSet^ DataSet {
    DataSet^ get ();
    private: void set (DataSet^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataSet](dataset-class-microsoft-dynamics-commerce-runtime-data-types.md)  
Returns [DataSet](https://technet.microsoft.com/library/bwy42y0e\(v=ax.60\)).  

## See Also

#### Reference

[DownloadDataSetResponse Class](downloaddatasetresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


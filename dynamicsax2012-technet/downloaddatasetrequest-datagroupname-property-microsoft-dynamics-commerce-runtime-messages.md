---
title: DownloadDataSetRequest.DataGroupName Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: DataGroupName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.DownloadDataSetRequest.DataGroupName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.downloaddatasetrequest.datagroupname(v=AX.60)
ms:contentKeyID: 62212299
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.DownloadDataSetRequest.DataGroupName
dev_langs:
- CSharp
- C++
- VB
---

# DataGroupName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the data object name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DataGroupName As String
    Get
    Set
'Usage
Dim instance As DownloadDataSetRequest
Dim value As String

value = instance.DataGroupName

instance.DataGroupName = value
```

``` csharp
[DataMemberAttribute]
public string DataGroupName { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ DataGroupName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The data object name.  

## See Also

#### Reference

[DownloadDataSetRequest Class](downloaddatasetrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


---
title: GetListingPublishStatusesRequest.ColumnSet Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ColumnSet Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetListingPublishStatusesRequest.ColumnSet
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getlistingpublishstatusesrequest.columnset(v=AX.60)
ms:contentKeyID: 62212275
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetListingPublishStatusesRequest.ColumnSet
dev_langs:
- CSharp
- C++
- VB
---

# ColumnSet Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the column set.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ColumnSet As ColumnSet
    Get
    Set
'Usage
Dim instance As GetListingPublishStatusesRequest
Dim value As ColumnSet

value = instance.ColumnSet

instance.ColumnSet = value
```

``` csharp
[DataMemberAttribute]
public ColumnSet ColumnSet { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property ColumnSet^ ColumnSet {
    ColumnSet^ get ();
    void set (ColumnSet^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  
The column set.  

## See Also

#### Reference

[GetListingPublishStatusesRequest Class](getlistingpublishstatusesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


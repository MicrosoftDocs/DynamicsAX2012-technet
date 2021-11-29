---
title: GetStockCountDataRequest.TransactionRecordsOnly Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: TransactionRecordsOnly Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetStockCountDataRequest.TransactionRecordsOnly
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getstockcountdatarequest.transactionrecordsonly(v=AX.60)
ms:contentKeyID: 65319842
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetStockCountDataRequest.TransactionRecordsOnly
dev_langs:
- CSharp
- C++
- VB
---

# TransactionRecordsOnly Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether transaction records are only required. No journal data will be included.

If set to true then JournalId must be specified also.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TransactionRecordsOnly As Boolean
    Get
    Set
'Usage
Dim instance As GetStockCountDataRequest
Dim value As Boolean

value = instance.TransactionRecordsOnly

instance.TransactionRecordsOnly = value
```

``` csharp
[DataMemberAttribute]
public bool TransactionRecordsOnly { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool TransactionRecordsOnly {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## Remarks

Default value is false.

## See Also

#### Reference

[GetStockCountDataRequest Class](getstockcountdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


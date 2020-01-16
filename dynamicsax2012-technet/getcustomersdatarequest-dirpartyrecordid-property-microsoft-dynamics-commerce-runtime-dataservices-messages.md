---
title: GetCustomersDataRequest.DirPartyRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: DirPartyRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetCustomersDataRequest.DirPartyRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getcustomersdatarequest.dirpartyrecordid(v=AX.60)
ms:contentKeyID: 65320196
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetCustomersDataRequest.DirPartyRecordId
dev_langs:
- CSharp
- C++
- VB
---

# DirPartyRecordId Property

Gets the record identifier for dirPartyTable of the customer to retrieve.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DirPartyRecordId As Long
    Get
    Private Set
'Usage
Dim instance As GetCustomersDataRequest
Dim value As Long

value = instance.DirPartyRecordId
```

``` csharp
[DataMemberAttribute]
public long DirPartyRecordId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property long long DirPartyRecordId {
    long long get ();
    private: void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The record identifier for dirPartyTable of the customer.  

## See Also

#### Reference

[GetCustomersDataRequest Class](getcustomersdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


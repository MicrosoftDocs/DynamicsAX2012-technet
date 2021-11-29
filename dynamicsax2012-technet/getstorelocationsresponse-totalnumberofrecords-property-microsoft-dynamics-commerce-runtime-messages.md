---
title: GetStoreLocationsResponse.TotalNumberOfRecords Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: TotalNumberOfRecords Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoreLocationsResponse.TotalNumberOfRecords
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getstorelocationsresponse.totalnumberofrecords(v=AX.60)
ms:contentKeyID: 49824370
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoreLocationsResponse.TotalNumberOfRecords
dev_langs:
- CSharp
- C++
- VB
---

# TotalNumberOfRecords Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the total number of records.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TotalNumberOfRecords As Integer
    Get
    Private Set
'Usage
Dim instance As GetStoreLocationsResponse
Dim value As Integer

value = instance.TotalNumberOfRecords
```

``` csharp
[DataMemberAttribute]
public int TotalNumberOfRecords { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property int TotalNumberOfRecords {
    int get ();
    private: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[GetStoreLocationsResponse Class](getstorelocationsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


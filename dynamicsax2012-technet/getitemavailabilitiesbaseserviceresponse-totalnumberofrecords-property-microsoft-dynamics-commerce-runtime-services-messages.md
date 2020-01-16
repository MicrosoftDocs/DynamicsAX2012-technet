---
title: GetItemAvailabilitiesBaseServiceResponse.TotalNumberOfRecords Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: TotalNumberOfRecords Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetItemAvailabilitiesBaseServiceResponse.TotalNumberOfRecords
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getitemavailabilitiesbaseserviceresponse.totalnumberofrecords(v=AX.60)
ms:contentKeyID: 62211621
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetItemAvailabilitiesBaseServiceResponse.TotalNumberOfRecords
dev_langs:
- CSharp
- C++
- VB
---

# TotalNumberOfRecords Property

Gets the total number of records.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property TotalNumberOfRecords As Integer
    Get
    Private Set
'Usage
Dim instance As GetItemAvailabilitiesBaseServiceResponse
Dim value As Integer

value = instance.TotalNumberOfRecords
```

``` csharp
[IgnoreDataMemberAttribute]
public int TotalNumberOfRecords { get; private set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property int TotalNumberOfRecords {
    int get ();
    private: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The total number of records.  

## See Also

#### Reference

[GetItemAvailabilitiesBaseServiceResponse Class](getitemavailabilitiesbaseserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


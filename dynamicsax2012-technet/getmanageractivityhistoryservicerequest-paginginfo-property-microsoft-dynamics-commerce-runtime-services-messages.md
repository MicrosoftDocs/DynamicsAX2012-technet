---
title: GetManagerActivityHistoryServiceRequest.PagingInfo Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: PagingInfo Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetManagerActivityHistoryServiceRequest.PagingInfo
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getmanageractivityhistoryservicerequest.paginginfo(v=AX.60)
ms:contentKeyID: 65320919
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetManagerActivityHistoryServiceRequest.PagingInfo
dev_langs:
- CSharp
- C++
- VB
---

# PagingInfo Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PagingInfo As PagingInfo
    Get
    Private Set
'Usage
Dim instance As GetManagerActivityHistoryServiceRequest
Dim value As PagingInfo

value = instance.PagingInfo
```

``` csharp
[DataMemberAttribute]
public PagingInfo PagingInfo { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property PagingInfo^ PagingInfo {
    PagingInfo^ get ();
    private: void set (PagingInfo^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PagingInfo](paginginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetManagerActivityHistoryServiceRequest Class](getmanageractivityhistoryservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


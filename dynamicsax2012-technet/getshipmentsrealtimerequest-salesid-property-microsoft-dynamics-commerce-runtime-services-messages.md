---
title: GetShipmentsRealtimeRequest.SalesId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: SalesId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetShipmentsRealtimeRequest.SalesId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getshipmentsrealtimerequest.salesid(v=AX.60)
ms:contentKeyID: 65322880
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetShipmentsRealtimeRequest.SalesId
dev_langs:
- CSharp
- C++
- VB
---

# SalesId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SalesId As String
    Get
    Private Set
'Usage
Dim instance As GetShipmentsRealtimeRequest
Dim value As String

value = instance.SalesId
```

``` csharp
[DataMemberAttribute]
public string SalesId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ SalesId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[GetShipmentsRealtimeRequest Class](getshipmentsrealtimerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


---
title: GetManagerActivityHistoryServiceRequest.StoreIds Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: StoreIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetManagerActivityHistoryServiceRequest.StoreIds
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getmanageractivityhistoryservicerequest.storeids(v=AX.60)
ms:contentKeyID: 65323214
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetManagerActivityHistoryServiceRequest.StoreIds
dev_langs:
- CSharp
- C++
- VB
---

# StoreIds Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property StoreIds As String()
    Get
    Private Set
'Usage
Dim instance As GetManagerActivityHistoryServiceRequest
Dim value As String()

value = instance.StoreIds
```

``` csharp
[DataMemberAttribute]
public string[] StoreIds { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property array<String^>^ StoreIds {
    array<String^>^ get ();
    private: void set (array<String^>^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\[\]  

## See Also

#### Reference

[GetManagerActivityHistoryServiceRequest Class](getmanageractivityhistoryservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


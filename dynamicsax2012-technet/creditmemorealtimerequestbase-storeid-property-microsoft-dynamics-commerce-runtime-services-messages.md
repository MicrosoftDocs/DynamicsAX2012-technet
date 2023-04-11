---
title: CreditMemoRealtimeRequestBase.StoreId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: StoreId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CreditMemoRealtimeRequestBase.StoreId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.creditmemorealtimerequestbase.storeid(v=AX.60)
ms:contentKeyID: 65319904
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CreditMemoRealtimeRequestBase.StoreId
dev_langs:
- CSharp
- C++
- VB
---

# StoreId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property StoreId As String
    Get
    Private Set
'Usage
Dim instance As CreditMemoRealtimeRequestBase
Dim value As String

value = instance.StoreId
```

``` csharp
[DataMemberAttribute]
public string StoreId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ StoreId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[CreditMemoRealtimeRequestBase Class](creditmemorealtimerequestbase-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


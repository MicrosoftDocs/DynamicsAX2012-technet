---
title: GetItemDeliveryOptionsDataRequest.StateId Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: StateId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetItemDeliveryOptionsDataRequest.StateId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getitemdeliveryoptionsdatarequest.stateid(v=AX.60)
ms:contentKeyID: 65315964
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetItemDeliveryOptionsDataRequest.StateId
dev_langs:
- CSharp
- C++
- VB
---

# StateId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the state id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property StateId As String
    Get
    Private Set
'Usage
Dim instance As GetItemDeliveryOptionsDataRequest
Dim value As String

value = instance.StateId
```

``` csharp
[DataMemberAttribute]
public string StateId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ StateId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetItemDeliveryOptionsDataRequest Class](getitemdeliveryoptionsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


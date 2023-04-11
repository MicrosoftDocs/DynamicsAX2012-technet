---
title: GetDeliveryOptionsRequest.FetchDeliveryOptionsForLines Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: FetchDeliveryOptionsForLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetDeliveryOptionsRequest.FetchDeliveryOptionsForLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getdeliveryoptionsrequest.fetchdeliveryoptionsforlines(v=AX.60)
ms:contentKeyID: 49838224
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetDeliveryOptionsRequest.FetchDeliveryOptionsForLines
dev_langs:
- CSharp
- C++
- VB
---

# FetchDeliveryOptionsForLines Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether to get the delivery options for line level or not.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property FetchDeliveryOptionsForLines As Boolean
    Get
    Private Set
'Usage
Dim instance As GetDeliveryOptionsRequest
Dim value As Boolean

value = instance.FetchDeliveryOptionsForLines
```

``` csharp
[DataMemberAttribute]
public bool FetchDeliveryOptionsForLines { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property bool FetchDeliveryOptionsForLines {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## Remarks

By default, the delivery options are fetched at order level.

## See Also

#### Reference

[GetDeliveryOptionsRequest Class](getdeliveryoptionsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


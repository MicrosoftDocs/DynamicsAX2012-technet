---
title: UpdatePriceServiceRequest.RestoreItemPrices Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: RestoreItemPrices Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UpdatePriceServiceRequest.RestoreItemPrices
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.updatepriceservicerequest.restoreitemprices(v=AX.60)
ms:contentKeyID: 62207258
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UpdatePriceServiceRequest.RestoreItemPrices
dev_langs:
- CSharp
- C++
- VB
---

# RestoreItemPrices Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether the item prices are to be restored.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property RestoreItemPrices As Boolean
    Get
    Private Set
'Usage
Dim instance As UpdatePriceServiceRequest
Dim value As Boolean

value = instance.RestoreItemPrices
```

``` csharp
[DataMemberAttribute]
public bool RestoreItemPrices { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property bool RestoreItemPrices {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[UpdatePriceServiceRequest Class](updatepriceservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


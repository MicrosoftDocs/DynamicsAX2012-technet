---
title: UpdatePriceServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: UpdatePriceServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UpdatePriceServiceRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.updatepriceservicerequest.updatepriceservicerequest(v=AX.60)
ms:contentKeyID: 65318639
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UpdatePriceServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# UpdatePriceServiceRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    transaction As SalesTransaction, _
    restoreItemPrices As Boolean _
)
'Usage
Dim transaction As SalesTransaction
Dim restoreItemPrices As Boolean

Dim instance As New UpdatePriceServiceRequest(transaction, _
    restoreItemPrices)
```

``` csharp
public UpdatePriceServiceRequest(
    SalesTransaction transaction,
    bool restoreItemPrices
)
```

``` c++
public:
UpdatePriceServiceRequest(
    SalesTransaction^ transaction, 
    bool restoreItemPrices
)
```

#### Parameters

  - transaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - restoreItemPrices  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[UpdatePriceServiceRequest Class](updatepriceservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


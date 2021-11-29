---
title: GetTransferOrderServiceResponse.TransferOrders Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: TransferOrders Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetTransferOrderServiceResponse.TransferOrders
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.gettransferorderserviceresponse.transferorders(v=AX.60)
ms:contentKeyID: 62210593
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetTransferOrderServiceResponse.TransferOrders
dev_langs:
- CSharp
- C++
- VB
---

# TransferOrders Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the transfer orders.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property TransferOrders As ReadOnlyCollection(Of TransferOrder)
    Get
    Private Set
'Usage
Dim instance As GetTransferOrderServiceResponse
Dim value As ReadOnlyCollection(Of TransferOrder)

value = instance.TransferOrders
```

``` csharp
public ReadOnlyCollection<TransferOrder> TransferOrders { get; private set; }
```

``` c++
public:
property ReadOnlyCollection<TransferOrder^>^ TransferOrders {
    ReadOnlyCollection<TransferOrder^>^ get ();
    private: void set (ReadOnlyCollection<TransferOrder^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[TransferOrder](transferorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetTransferOrderServiceResponse Class](gettransferorderserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


---
title: GetTransferOrderResponse.TransferOrders Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: TransferOrders Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetTransferOrderResponse.TransferOrders
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.gettransferorderresponse.transferorders(v=AX.60)
ms:contentKeyID: 62204736
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetTransferOrderResponse.TransferOrders
dev_langs:
- CSharp
- C++
- VB
---

# TransferOrders Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TransferOrders As ReadOnlyCollection(Of TransferOrder)
    Get
    Private Set
'Usage
Dim instance As GetTransferOrderResponse
Dim value As ReadOnlyCollection(Of TransferOrder)

value = instance.TransferOrders
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<TransferOrder> TransferOrders { get; private set; }
```

``` c++
[DataMemberAttribute]
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

[GetTransferOrderResponse Class](gettransferorderresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


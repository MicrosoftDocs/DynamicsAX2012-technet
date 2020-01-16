---
title: SaveTransferOrderRequest.TransferOrder Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: TransferOrder Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.SaveTransferOrderRequest.TransferOrder
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.savetransferorderrequest.transferorder(v=AX.60)
ms:contentKeyID: 62212248
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.SaveTransferOrderRequest.TransferOrder
dev_langs:
- CSharp
- C++
- VB
---

# TransferOrder Property

Gets or sets the transfer order to save.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TransferOrder As TransferOrder
    Get
    Set
'Usage
Dim instance As SaveTransferOrderRequest
Dim value As TransferOrder

value = instance.TransferOrder

instance.TransferOrder = value
```

``` csharp
[DataMemberAttribute]
public TransferOrder TransferOrder { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property TransferOrder^ TransferOrder {
    TransferOrder^ get ();
    void set (TransferOrder^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TransferOrder](transferorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [TransferOrder](transferorder-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[SaveTransferOrderRequest Class](savetransferorderrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


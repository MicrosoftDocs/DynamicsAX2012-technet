---
title: SaveTransferOrderServiceRequest.TransferOrder Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: TransferOrder Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveTransferOrderServiceRequest.TransferOrder
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.savetransferorderservicerequest.transferorder(v=AX.60)
ms:contentKeyID: 62209871
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveTransferOrderServiceRequest.TransferOrder
dev_langs:
- CSharp
- C++
- VB
---

# TransferOrder Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the transfer order to be saved.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TransferOrder As TransferOrder
    Get
    Set
'Usage
Dim instance As SaveTransferOrderServiceRequest
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

[SaveTransferOrderServiceRequest Class](savetransferorderservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


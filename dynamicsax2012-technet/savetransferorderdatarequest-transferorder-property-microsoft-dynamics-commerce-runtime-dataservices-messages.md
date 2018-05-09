---
title: SaveTransferOrderDataRequest.TransferOrder Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: TransferOrder Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SaveTransferOrderDataRequest.TransferOrder
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.savetransferorderdatarequest.transferorder(v=AX.60)
ms:contentKeyID: 65322374
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SaveTransferOrderDataRequest.TransferOrder
dev_langs:
- CSharp
- C++
- VB
---

# TransferOrder Property

Gets the transfer order to be saved.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TransferOrder As TransferOrder
    Get
    Private Set
'Usage
Dim instance As SaveTransferOrderDataRequest
Dim value As TransferOrder

value = instance.TransferOrder
```

``` csharp
[DataMemberAttribute]
public TransferOrder TransferOrder { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property TransferOrder^ TransferOrder {
    TransferOrder^ get ();
    private: void set (TransferOrder^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TransferOrder](transferorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [TransferOrder](transferorder-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[SaveTransferOrderDataRequest Class](savetransferorderdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


---
title: SaveCartRequest.OperationType Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: OperationType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.SaveCartRequest.OperationType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.savecartrequest.operationtype(v=AX.60)
ms:contentKeyID: 62209968
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.SaveCartRequest.OperationType
dev_langs:
- CSharp
- C++
- VB
---

# OperationType Property

Gets the type of the operation.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property OperationType As TransactionOperationType
    Get
    Private Set
'Usage
Dim instance As SaveCartRequest
Dim value As TransactionOperationType

value = instance.OperationType
```

``` csharp
[DataMemberAttribute]
public TransactionOperationType OperationType { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property TransactionOperationType OperationType {
    TransactionOperationType get ();
    private: void set (TransactionOperationType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionOperationType](transactionoperationtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [TransactionOperationType](transactionoperationtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[SaveCartRequest Class](savecartrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


---
title: SaveStoreOperationRequest.TenderDropAndDeclareOperation Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: TenderDropAndDeclareOperation Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.SaveStoreOperationRequest.TenderDropAndDeclareOperation
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.savestoreoperationrequest.tenderdropanddeclareoperation(v=AX.60)
ms:contentKeyID: 62210650
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.SaveStoreOperationRequest.TenderDropAndDeclareOperation
dev_langs:
- CSharp
- C++
- VB
---

# TenderDropAndDeclareOperation Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the tender drop and declaration by cashier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TenderDropAndDeclareOperation As DropAndDeclareTransaction
    Get
    Set
'Usage
Dim instance As SaveStoreOperationRequest
Dim value As DropAndDeclareTransaction

value = instance.TenderDropAndDeclareOperation

instance.TenderDropAndDeclareOperation = value
```

``` csharp
[DataMemberAttribute]
public DropAndDeclareTransaction TenderDropAndDeclareOperation { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property DropAndDeclareTransaction^ TenderDropAndDeclareOperation {
    DropAndDeclareTransaction^ get ();
    void set (DropAndDeclareTransaction^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DropAndDeclareTransaction](dropanddeclaretransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [DropAndDeclareTransaction](dropanddeclaretransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[SaveStoreOperationRequest Class](savestoreoperationrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


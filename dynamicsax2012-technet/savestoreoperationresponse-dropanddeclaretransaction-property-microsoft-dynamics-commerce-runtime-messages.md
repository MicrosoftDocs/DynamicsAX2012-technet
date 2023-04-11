---
title: SaveStoreOperationResponse.DropAndDeclareTransaction Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: DropAndDeclareTransaction Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.SaveStoreOperationResponse.DropAndDeclareTransaction
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.savestoreoperationresponse.dropanddeclaretransaction(v=AX.60)
ms:contentKeyID: 62211247
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.SaveStoreOperationResponse.DropAndDeclareTransaction
dev_langs:
- CSharp
- C++
- VB
---

# DropAndDeclareTransaction Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the tender drop and declare operation.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DropAndDeclareTransaction As DropAndDeclareTransaction
    Get
    Private Set
'Usage
Dim instance As SaveStoreOperationResponse
Dim value As DropAndDeclareTransaction

value = instance.DropAndDeclareTransaction
```

``` csharp
[DataMemberAttribute]
public DropAndDeclareTransaction DropAndDeclareTransaction { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property DropAndDeclareTransaction^ DropAndDeclareTransaction {
    DropAndDeclareTransaction^ get ();
    private: void set (DropAndDeclareTransaction^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DropAndDeclareTransaction](dropanddeclaretransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [DropAndDeclareTransaction](dropanddeclaretransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[SaveStoreOperationResponse Class](savestoreoperationresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


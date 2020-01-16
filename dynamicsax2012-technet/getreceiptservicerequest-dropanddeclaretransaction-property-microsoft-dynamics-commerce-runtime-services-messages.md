---
title: GetReceiptServiceRequest.DropAndDeclareTransaction Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: DropAndDeclareTransaction Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReceiptServiceRequest.DropAndDeclareTransaction
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getreceiptservicerequest.dropanddeclaretransaction(v=AX.60)
ms:contentKeyID: 62203797
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReceiptServiceRequest.DropAndDeclareTransaction
dev_langs:
- CSharp
- C++
- VB
---

# DropAndDeclareTransaction Property

Gets or sets the transaction for a drop and declare transaction if any.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DropAndDeclareTransaction As DropAndDeclareTransaction
    Get
    Set
'Usage
Dim instance As GetReceiptServiceRequest
Dim value As DropAndDeclareTransaction

value = instance.DropAndDeclareTransaction

instance.DropAndDeclareTransaction = value
```

``` csharp
[DataMemberAttribute]
public DropAndDeclareTransaction DropAndDeclareTransaction { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property DropAndDeclareTransaction^ DropAndDeclareTransaction {
    DropAndDeclareTransaction^ get ();
    void set (DropAndDeclareTransaction^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DropAndDeclareTransaction](dropanddeclaretransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [DropAndDeclareTransaction](dropanddeclaretransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetReceiptServiceRequest Class](getreceiptservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


---
title: TransactionServiceProfile.Protocol Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Protocol Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionServiceProfile.Protocol
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.transactionserviceprofile.protocol(v=AX.60)
ms:contentKeyID: 62212059
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionServiceProfile.Protocol
dev_langs:
- CSharp
- C++
- VB
---

# Protocol Property

Gets the transaction service protocol.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TSPROTOCOL")> _
<IgnoreDataMemberAttribute> _
Public ReadOnly Property Protocol As Integer
    Get
'Usage
Dim instance As TransactionServiceProfile
Dim value As Integer

value = instance.Protocol
```

``` csharp
[ColumnAttribute("TSPROTOCOL")]
[IgnoreDataMemberAttribute]
public int Protocol { get; }
```

``` c++
[ColumnAttribute(L"TSPROTOCOL")]
[IgnoreDataMemberAttribute]
public:
property int Protocol {
    int get ();
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[TransactionServiceProfile Class](transactionserviceprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


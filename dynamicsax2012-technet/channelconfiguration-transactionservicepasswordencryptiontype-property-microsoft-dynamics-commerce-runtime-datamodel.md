---
title: ChannelConfiguration.TransactionServicePasswordEncryptionType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TransactionServicePasswordEncryptionType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.TransactionServicePasswordEncryptionType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channelconfiguration.transactionservicepasswordencryptiontype(v=AX.60)
ms:contentKeyID: 49844589
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.TransactionServicePasswordEncryptionType
dev_langs:
- CSharp
- C++
- VB
---

# TransactionServicePasswordEncryptionType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the transaction service password encryption type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public ReadOnly Property TransactionServicePasswordEncryptionType As String
    Get
'Usage
Dim instance As ChannelConfiguration
Dim value As String

value = instance.TransactionServicePasswordEncryptionType
```

``` csharp
[IgnoreDataMemberAttribute]
public string TransactionServicePasswordEncryptionType { get; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property String^ TransactionServicePasswordEncryptionType {
    String^ get ();
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ChannelConfiguration Class](channelconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


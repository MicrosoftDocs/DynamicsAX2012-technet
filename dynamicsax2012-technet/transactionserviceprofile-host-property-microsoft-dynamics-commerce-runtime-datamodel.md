---
title: TransactionServiceProfile.Host Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Host Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionServiceProfile.Host
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.transactionserviceprofile.host(v=AX.60)
ms:contentKeyID: 62205335
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionServiceProfile.Host
dev_langs:
- CSharp
- C++
- VB
---

# Host Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the transaction service host.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TSHOST")> _
<IgnoreDataMemberAttribute> _
Public ReadOnly Property Host As String
    Get
'Usage
Dim instance As TransactionServiceProfile
Dim value As String

value = instance.Host
```

``` csharp
[ColumnAttribute("TSHOST")]
[IgnoreDataMemberAttribute]
public string Host { get; }
```

``` c++
[ColumnAttribute(L"TSHOST")]
[IgnoreDataMemberAttribute]
public:
property String^ Host {
    String^ get ();
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TransactionServiceProfile Class](transactionserviceprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


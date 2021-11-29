---
title: TransactionServiceProfile.Port Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Port Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionServiceProfile.Port
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.transactionserviceprofile.port(v=AX.60)
ms:contentKeyID: 62203748
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionServiceProfile.Port
dev_langs:
- CSharp
- C++
- VB
---

# Port Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the transaction service port.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("TSPORT")> _
Public ReadOnly Property Port As Integer
    Get
'Usage
Dim instance As TransactionServiceProfile
Dim value As Integer

value = instance.Port
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("TSPORT")]
public int Port { get; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"TSPORT")]
public:
property int Port {
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


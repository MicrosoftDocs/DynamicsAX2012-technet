---
title: TransactionServiceProfile.ServerCertificateDns Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ServerCertificateDns Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionServiceProfile.ServerCertificateDns
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.transactionserviceprofile.servercertificatedns(v=AX.60)
ms:contentKeyID: 62208077
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionServiceProfile.ServerCertificateDns
dev_langs:
- CSharp
- C++
- VB
---

# ServerCertificateDns Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the transaction service server certificate DNS.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TSSERVERCERTIFICATEDNS")> _
<IgnoreDataMemberAttribute> _
Public ReadOnly Property ServerCertificateDns As String
    Get
'Usage
Dim instance As TransactionServiceProfile
Dim value As String

value = instance.ServerCertificateDns
```

``` csharp
[ColumnAttribute("TSSERVERCERTIFICATEDNS")]
[IgnoreDataMemberAttribute]
public string ServerCertificateDns { get; }
```

``` c++
[ColumnAttribute(L"TSSERVERCERTIFICATEDNS")]
[IgnoreDataMemberAttribute]
public:
property String^ ServerCertificateDns {
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


---
title: TransactionServiceProfile.EncryptedPassword Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EncryptedPassword Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionServiceProfile.EncryptedPassword
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.transactionserviceprofile.encryptedpassword(v=AX.60)
ms:contentKeyID: 62207975
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionServiceProfile.EncryptedPassword
dev_langs:
- CSharp
- C++
- VB
---

# EncryptedPassword Property

Gets the transaction service encrypted password.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("TSENCRYPTEDPASSWORD")> _
Public ReadOnly Property EncryptedPassword As String
    Get
'Usage
Dim instance As TransactionServiceProfile
Dim value As String

value = instance.EncryptedPassword
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("TSENCRYPTEDPASSWORD")]
public string EncryptedPassword { get; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"TSENCRYPTEDPASSWORD")]
public:
property String^ EncryptedPassword {
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


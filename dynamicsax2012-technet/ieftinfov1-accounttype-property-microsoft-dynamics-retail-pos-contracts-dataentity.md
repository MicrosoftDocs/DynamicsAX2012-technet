---
title: IEFTInfoV1.AccountType Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: AccountType Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfoV1.AccountType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ieftinfov1.accounttype(v=AX.60)
ms:contentKeyID: 47129011
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfoV1.AccountType
dev_langs:
- CSharp
- C++
- VB
---

# AccountType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the type of the account (for example, checking, saving, etc.).

A debit operation, for example, may require that the account type be specified.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property AccountType As String
    Get
    Set
'Usage
Dim instance As IEFTInfoV1
Dim value As String

value = instance.AccountType

instance.AccountType = value
```

``` csharp
string AccountType { get; set; }
```

``` c++
property String^ AccountType {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The type of the account.  

## See Also

#### Reference

[IEFTInfoV1 Interface](ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)


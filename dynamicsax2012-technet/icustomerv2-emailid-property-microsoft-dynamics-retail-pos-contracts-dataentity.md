---
title: ICustomerV2.EmailId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: EmailId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerV2.EmailId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.icustomerv2.emailid(v=AX.60)
ms:contentKeyID: 50496739
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerV2.EmailId
dev_langs:
- CSharp
- C++
- VB
---

# EmailId Property

Gets or sets the email rec id.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property EmailId As Long
    Get
    Set
'Usage
Dim instance As ICustomerV2
Dim value As Long

value = instance.EmailId

instance.EmailId = value
```

``` csharp
long EmailId { get; set; }
```

``` c++
property long long EmailId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The email rec id.  

## See Also

#### Reference

[ICustomerV2 Interface](icustomerv2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)


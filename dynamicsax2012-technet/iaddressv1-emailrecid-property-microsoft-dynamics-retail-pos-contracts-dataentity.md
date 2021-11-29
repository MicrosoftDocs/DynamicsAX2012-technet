---
title: IAddressV1.EmailRecId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: EmailRecId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IAddressV1.EmailRecId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iaddressv1.emailrecid(v=AX.60)
ms:contentKeyID: 47128276
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IAddressV1.EmailRecId
dev_langs:
- CSharp
- C++
- VB
---

# EmailRecId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the email record ID.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property EmailRecId As Long
    Get
    Set
'Usage
Dim instance As IAddressV1
Dim value As Long

value = instance.EmailRecId

instance.EmailRecId = value
```

``` csharp
long EmailRecId { get; set; }
```

``` c++
property long long EmailRecId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The email record ID.  

## See Also

#### Reference

[IAddressV1 Interface](iaddressv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)


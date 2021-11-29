---
title: ICustomerV2.UrlId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: UrlId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerV2.UrlId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.icustomerv2.urlid(v=AX.60)
ms:contentKeyID: 50496947
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerV2.UrlId
dev_langs:
- CSharp
- C++
- VB
---

# UrlId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the URL rec id.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property UrlId As Long
    Get
    Set
'Usage
Dim instance As ICustomerV2
Dim value As Long

value = instance.UrlId

instance.UrlId = value
```

``` csharp
long UrlId { get; set; }
```

``` c++
property long long UrlId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The URL rec id.  

## See Also

#### Reference

[ICustomerV2 Interface](icustomerv2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)


---
title: IAddressV4.DistrictRecId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: DistrictRecId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IAddressV4.DistrictRecId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iaddressv4.districtrecid(v=AX.60)
ms:contentKeyID: 62201878
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IAddressV4.DistrictRecId
dev_langs:
- CSharp
- C++
- VB
---

# DistrictRecId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

RecId of District in Ax table

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property DistrictRecId As Long
    Get
    Set
'Usage
Dim instance As IAddressV4
Dim value As Long

value = instance.DistrictRecId

instance.DistrictRecId = value
```

``` csharp
long DistrictRecId { get; set; }
```

``` c++
property long long DistrictRecId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[IAddressV4 Interface](iaddressv4-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)


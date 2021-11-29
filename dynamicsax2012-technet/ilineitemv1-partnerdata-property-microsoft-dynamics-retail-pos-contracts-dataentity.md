---
title: ILineItemV1.PartnerData Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: PartnerData Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILineItemV1.PartnerData
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ilineitemv1.partnerdata(v=AX.60)
ms:contentKeyID: 49831438
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILineItemV1.PartnerData
dev_langs:
- CSharp
- C++
- VB
---

# PartnerData Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Get dynamic object that hold partner's data.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property PartnerData As Object
    Get
'Usage
Dim instance As ILineItemV1
Dim value As Object

value = instance.PartnerData
```

``` csharp
Object PartnerData { get; }
```

``` c++
property Object^ PartnerData {
    Object^ get ();
}
```

#### Property Value

Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
Returns [Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\)).  

## Remarks

saleItem.PartnerData.MS\_NewProperty = "value";

## See Also

#### Reference

[ILineItemV1 Interface](ilineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)


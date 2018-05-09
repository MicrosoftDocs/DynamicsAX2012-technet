---
title: IPharmacySalesLineItem Interface (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: IPharmacySalesLineItem Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPharmacySalesLineItem
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.ipharmacysaleslineitem(v=AX.60)
ms:contentKeyID: 49842119
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPharmacySalesLineItem
dev_langs:
- CSharp
- C++
- VB
---

# IPharmacySalesLineItem Interface

IPharmacySalesLineItem interface.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("1451604C-BEBD-434E-99E7-4D11DFDDC5FF")> _
Public Interface IPharmacySalesLineItem _
    Inherits ISaleLineItem, ITaxableItem, ILineItem, ILineItemV1,  _
    ISaleLineItemV1, ISaleLineItemV2, ISaleLineItemV3, ISaleLineItemV4, IPharmacySalesLineItemV1
'Usage
Dim instance As IPharmacySalesLineItem
```

``` csharp
[GuidAttribute("1451604C-BEBD-434E-99E7-4D11DFDDC5FF")]
public interface IPharmacySalesLineItem : ISaleLineItem, 
    ITaxableItem, ILineItem, ILineItemV1, ISaleLineItemV1, ISaleLineItemV2, 
    ISaleLineItemV3, ISaleLineItemV4, IPharmacySalesLineItemV1
```

``` c++
[GuidAttribute(L"1451604C-BEBD-434E-99E7-4D11DFDDC5FF")]
public interface class IPharmacySalesLineItem : ISaleLineItem, 
    ITaxableItem, ILineItem, ILineItemV1, ISaleLineItemV1, ISaleLineItemV2, 
    ISaleLineItemV3, ISaleLineItemV4, IPharmacySalesLineItemV1
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)


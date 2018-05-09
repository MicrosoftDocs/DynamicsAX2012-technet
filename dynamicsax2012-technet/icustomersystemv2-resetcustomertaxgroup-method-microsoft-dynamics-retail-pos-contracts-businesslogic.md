---
title: ICustomerSystemV2.ResetCustomerTaxGroup Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: ResetCustomerTaxGroup Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ICustomerSystemV2.ResetCustomerTaxGroup(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxableItem,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.businesslogic.icustomersystemv2.resetcustomertaxgroup(v=AX.60)
ms:contentKeyID: 50496859
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ICustomerSystemV2.ResetCustomerTaxGroup
dev_langs:
- CSharp
- C++
- VB
---

# ResetCustomerTaxGroup Method

**Note: This API is now obsolete.**

Resets the customer tax group.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<ObsoleteAttribute("This method is obsolete. Please use ResetCustomerTaxGroup(ITaxableItem) instead.")> _
Sub ResetCustomerTaxGroup ( _
    taxableItem As ITaxableItem, _
    applyLineShippingAddress As Boolean _
)
'Usage
Dim instance As ICustomerSystemV2
Dim taxableItem As ITaxableItem
Dim applyLineShippingAddress As Boolean

instance.ResetCustomerTaxGroup(taxableItem, _
    applyLineShippingAddress)
```

``` csharp
[ObsoleteAttribute("This method is obsolete. Please use ResetCustomerTaxGroup(ITaxableItem) instead.")]
void ResetCustomerTaxGroup(
    ITaxableItem taxableItem,
    bool applyLineShippingAddress
)
```

``` c++
[ObsoleteAttribute(L"This method is obsolete. Please use ResetCustomerTaxGroup(ITaxableItem) instead.")]
void ResetCustomerTaxGroup(
    ITaxableItem^ taxableItem, 
    bool applyLineShippingAddress
)
```

#### Parameters

  - taxableItem  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxableItem](itaxableitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - applyLineShippingAddress  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[ICustomerSystemV2 Interface](icustomersystemv2-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)


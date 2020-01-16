---
title: ISaleLineItemV1.ShippingAddress Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ShippingAddress Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.ShippingAddress
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.isalelineitemv1.shippingaddress(v=AX.60)
ms:contentKeyID: 49841386
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.ShippingAddress
dev_langs:
- CSharp
- C++
- VB
---

# ShippingAddress Property

Gets or sets shipping address.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property ShippingAddress As IAddress
    Get
    Set
'Usage
Dim instance As ISaleLineItemV1
Dim value As IAddress

value = instance.ShippingAddress

instance.ShippingAddress = value
```

``` csharp
IAddress ShippingAddress { get; set; }
```

``` c++
property IAddress^ ShippingAddress {
    IAddress^ get ();
    void set (IAddress^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IAddress](iaddress-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
Returns [IAddress](iaddress-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md).  

## See Also

#### Reference

[ISaleLineItemV1 Interface](isalelineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)


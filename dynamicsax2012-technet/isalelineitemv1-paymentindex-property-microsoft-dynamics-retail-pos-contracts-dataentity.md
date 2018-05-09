---
title: ISaleLineItemV1.PaymentIndex Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: PaymentIndex Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.PaymentIndex
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.isalelineitemv1.paymentindex(v=AX.60)
ms:contentKeyID: 49819674
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.PaymentIndex
dev_langs:
- CSharp
- C++
- VB
---

# PaymentIndex Property

The ID of the tender that has already been used to pay the item

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property PaymentIndex As Integer
    Get
    Set
'Usage
Dim instance As ISaleLineItemV1
Dim value As Integer

value = instance.PaymentIndex

instance.PaymentIndex = value
```

``` csharp
int PaymentIndex { get; set; }
```

``` c++
property int PaymentIndex {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[ISaleLineItemV1 Interface](isalelineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)


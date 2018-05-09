---
title: ICustomerPaymentTransactionV1.Capture Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: Capture Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerPaymentTransactionV1.Capture
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.icustomerpaymenttransactionv1.capture(v=AX.60)
ms:contentKeyID: 49844020
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerPaymentTransactionV1.Capture
dev_langs:
- CSharp
- C++
- VB
---

# Capture Property

Conclude transaction capture state.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property Capture As Boolean
    Get
    Set
'Usage
Dim instance As ICustomerPaymentTransactionV1
Dim value As Boolean

value = instance.Capture

instance.Capture = value
```

``` csharp
bool Capture { get; set; }
```

``` c++
property bool Capture {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ICustomerPaymentTransactionV1 Interface](icustomerpaymenttransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)


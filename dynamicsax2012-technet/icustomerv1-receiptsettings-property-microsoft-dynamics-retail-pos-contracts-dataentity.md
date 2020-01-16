---
title: ICustomerV1.ReceiptSettings Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ReceiptSettings Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerV1.ReceiptSettings
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.icustomerv1.receiptsettings(v=AX.60)
ms:contentKeyID: 47128437
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerV1.ReceiptSettings
dev_langs:
- CSharp
- C++
- VB
---

# ReceiptSettings Property

Indicates whether the customer requests a printed receipt or a receipt sent in an email.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property ReceiptSettings As ReceiptSettings
    Get
    Set
'Usage
Dim instance As ICustomerV1
Dim value As ReceiptSettings

value = instance.ReceiptSettings

instance.ReceiptSettings = value
```

``` csharp
ReceiptSettings ReceiptSettings { get; set; }
```

``` c++
property ReceiptSettings ReceiptSettings {
    ReceiptSettings get ();
    void set (ReceiptSettings value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ReceiptSettings](receiptsettings-enumeration-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
The [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ReceiptSettings](receiptsettings-enumeration-microsoft-dynamics-retail-pos-contracts-dataentity.md) value.  

## See Also

#### Reference

[ICustomerV1 Interface](icustomerv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)


---
title: ICustomerV1.MandatoryCreditLimit Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: MandatoryCreditLimit Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerV1.MandatoryCreditLimit
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.icustomerv1.mandatorycreditlimit(v=AX.60)
ms:contentKeyID: 47128499
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerV1.MandatoryCreditLimit
dev_langs:
- CSharp
- C++
- VB
---

# MandatoryCreditLimit Property

True if a mandatory credit limit is set.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property MandatoryCreditLimit As Boolean
    Get
    Set
'Usage
Dim instance As ICustomerV1
Dim value As Boolean

value = instance.MandatoryCreditLimit

instance.MandatoryCreditLimit = value
```

``` csharp
bool MandatoryCreditLimit { get; set; }
```

``` c++
property bool MandatoryCreditLimit {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
The [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)) value.  

## See Also

#### Reference

[ICustomerV1 Interface](icustomerv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)


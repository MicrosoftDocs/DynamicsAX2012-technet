---
title: IEFTInfoV3.IsPendingCustomerSignature Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: IsPendingCustomerSignature Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfoV3.IsPendingCustomerSignature
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ieftinfov3.ispendingcustomersignature(v=AX.60)
ms:contentKeyID: 62205788
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfoV3.IsPendingCustomerSignature
dev_langs:
- CSharp
- C++
- VB
---

# IsPendingCustomerSignature Property

Gets or sets the customer sign expectation flag If it is true, it will be necessary to ask the customer to sign off the bank slip

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property IsPendingCustomerSignature As Boolean
    Get
    Set
'Usage
Dim instance As IEFTInfoV3
Dim value As Boolean

value = instance.IsPendingCustomerSignature

instance.IsPendingCustomerSignature = value
```

``` csharp
bool IsPendingCustomerSignature { get; set; }
```

``` c++
property bool IsPendingCustomerSignature {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[IEFTInfoV3 Interface](ieftinfov3-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)


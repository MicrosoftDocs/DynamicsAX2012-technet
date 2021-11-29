---
title: IEFTInfoV1.TenderType Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: TenderType Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfoV1.TenderType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ieftinfov1.tendertype(v=AX.60)
ms:contentKeyID: 47128786
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfoV1.TenderType
dev_langs:
- CSharp
- C++
- VB
---

# TenderType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets an ID that represents the tender that is used.

The TenderType field is the ID of the payment made for the purchase.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property TenderType As Integer
    Get
    Set
'Usage
Dim instance As IEFTInfoV1
Dim value As Integer

value = instance.TenderType

instance.TenderType = value
```

``` csharp
int TenderType { get; set; }
```

``` c++
property int TenderType {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)) value.  

## See Also

#### Reference

[IEFTInfoV1 Interface](ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)


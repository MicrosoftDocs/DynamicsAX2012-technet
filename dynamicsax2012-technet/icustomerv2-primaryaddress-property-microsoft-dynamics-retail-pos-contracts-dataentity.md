---
title: ICustomerV2.PrimaryAddress Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: PrimaryAddress Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerV2.PrimaryAddress
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.icustomerv2.primaryaddress(v=AX.60)
ms:contentKeyID: 49830698
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerV2.PrimaryAddress
dev_langs:
- CSharp
- C++
- VB
---

# PrimaryAddress Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property PrimaryAddress As IAddress
    Get
    Set
'Usage
Dim instance As ICustomerV2
Dim value As IAddress

value = instance.PrimaryAddress

instance.PrimaryAddress = value
```

``` csharp
IAddress PrimaryAddress { get; set; }
```

``` c++
property IAddress^ PrimaryAddress {
    IAddress^ get ();
    void set (IAddress^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IAddress](iaddress-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
Returns [IAddress](iaddress-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md).  

## See Also

#### Reference

[ICustomerV2 Interface](icustomerv2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)


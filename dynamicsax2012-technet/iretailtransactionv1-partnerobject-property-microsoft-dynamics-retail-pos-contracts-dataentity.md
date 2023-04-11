---
title: IRetailTransactionV1.PartnerObject Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: PartnerObject Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.PartnerObject
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iretailtransactionv1.partnerobject(v=AX.60)
ms:contentKeyID: 49832351
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.PartnerObject
dev_langs:
- CSharp
- C++
- VB
---

# PartnerObject Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

An object which can hold any information that localization might want to add to the RetailTransaction

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property PartnerObject As Object
    Get
    Set
'Usage
Dim instance As IRetailTransactionV1
Dim value As Object

value = instance.PartnerObject

instance.PartnerObject = value
```

``` csharp
Object PartnerObject { get; set; }
```

``` c++
property Object^ PartnerObject {
    Object^ get ();
    void set (Object^ value);
}
```

#### Property Value

Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
Returns [Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\)).  

## See Also

#### Reference

[IRetailTransactionV1 Interface](iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)


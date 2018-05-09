---
title: ICustomerV3.CustomerAffiliations Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: CustomerAffiliations Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerV3.CustomerAffiliations
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.icustomerv3.customeraffiliations(v=AX.60)
ms:contentKeyID: 62202853
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerV3.CustomerAffiliations
dev_langs:
- CSharp
- C++
- VB
---

# CustomerAffiliations Property

Get or set customer affiliatins.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property CustomerAffiliations As ICollection(Of ICustomerAffiliation)
    Get
    Set
'Usage
Dim instance As ICustomerV3
Dim value As ICollection(Of ICustomerAffiliation)

value = instance.CustomerAffiliations

instance.CustomerAffiliations = value
```

``` csharp
ICollection<ICustomerAffiliation> CustomerAffiliations { get; set; }
```

``` c++
property ICollection<ICustomerAffiliation^>^ CustomerAffiliations {
    ICollection<ICustomerAffiliation^>^ get ();
    void set (ICollection<ICustomerAffiliation^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/en-us/library/92t2ye13\(v=ax.60\))\<[ICustomerAffiliation](icustomeraffiliation-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)\>  
Customer affiliations.  

## See Also

#### Reference

[ICustomerV3 Interface](icustomerv3-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)


---
title: ICustomerV1.PartyType Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: PartyType Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerV1.PartyType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.icustomerv1.partytype(v=AX.60)
ms:contentKeyID: 47127993
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerV1.PartyType
dev_langs:
- CSharp
- C++
- VB
---

# PartyType Property

**Note: This API is now obsolete.**

Gets or sets the party type for this customer (person or organization).

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<ObsoleteAttribute("This attribute is not used anymore. Use RelationType typed one instead")> _
Property PartyType As DirPartyType
    Get
    Set
'Usage
Dim instance As ICustomerV1
Dim value As DirPartyType

value = instance.PartyType

instance.PartyType = value
```

``` csharp
[ObsoleteAttribute("This attribute is not used anymore. Use RelationType typed one instead")]
DirPartyType PartyType { get; set; }
```

``` c++
[ObsoleteAttribute(L"This attribute is not used anymore. Use RelationType typed one instead")]
property DirPartyType PartyType {
    DirPartyType get ();
    void set (DirPartyType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.DirPartyType](dirpartytype-enumeration-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
The [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.DirPartyType](dirpartytype-enumeration-microsoft-dynamics-retail-pos-contracts-dataentity.md) value.  

## See Also

#### Reference

[ICustomerV1 Interface](icustomerv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)


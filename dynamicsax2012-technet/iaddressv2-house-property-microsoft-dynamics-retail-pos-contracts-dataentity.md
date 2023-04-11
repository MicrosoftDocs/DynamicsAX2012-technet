---
title: IAddressV2.House Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: House Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IAddressV2.House
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iaddressv2.house(v=AX.60)
ms:contentKeyID: 49838280
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IAddressV2.House
dev_langs:
- CSharp
- C++
- VB
---

# House Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Note: This API is now obsolete.**

Specific to Russia

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<ObsoleteAttribute("Used in AX only, do not use in POS")> _
Property House As String
    Get
    Set
'Usage
Dim instance As IAddressV2
Dim value As String

value = instance.House

instance.House = value
```

``` csharp
[ObsoleteAttribute("Used in AX only, do not use in POS")]
string House { get; set; }
```

``` c++
[ObsoleteAttribute(L"Used in AX only, do not use in POS")]
property String^ House {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[IAddressV2 Interface](iaddressv2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)


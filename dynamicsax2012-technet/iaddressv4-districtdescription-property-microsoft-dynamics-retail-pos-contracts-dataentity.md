---
title: IAddressV4.DistrictDescription Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: DistrictDescription Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IAddressV4.DistrictDescription
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iaddressv4.districtdescription(v=AX.60)
ms:contentKeyID: 62202536
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IAddressV4.DistrictDescription
dev_langs:
- CSharp
- C++
- VB
---

# DistrictDescription Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Description of district (Russia)

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property DistrictDescription As String
    Get
    Set
'Usage
Dim instance As IAddressV4
Dim value As String

value = instance.DistrictDescription

instance.DistrictDescription = value
```

``` csharp
string DistrictDescription { get; set; }
```

``` c++
property String^ DistrictDescription {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[IAddressV4 Interface](iaddressv4-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)


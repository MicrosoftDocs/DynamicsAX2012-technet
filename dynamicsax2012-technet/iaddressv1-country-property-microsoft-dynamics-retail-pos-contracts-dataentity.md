---
title: IAddressV1.Country Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: Country Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IAddressV1.Country
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iaddressv1.country(v=AX.60)
ms:contentKeyID: 47129020
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IAddressV1.Country
dev_langs:
- CSharp
- C++
- VB
---

# Country Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the country or region ID.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property Country As String
    Get
    Set
'Usage
Dim instance As IAddressV1
Dim value As String

value = instance.Country

instance.Country = value
```

``` csharp
string Country { get; set; }
```

``` c++
property String^ Country {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)) value.  

## See Also

#### Reference

[IAddressV1 Interface](iaddressv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)


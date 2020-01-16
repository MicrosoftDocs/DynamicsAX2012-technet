---
title: IAddressV4.CountyDescription Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: CountyDescription Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IAddressV4.CountyDescription
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iaddressv4.countydescription(v=AX.60)
ms:contentKeyID: 62204995
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IAddressV4.CountyDescription
dev_langs:
- CSharp
- C++
- VB
---

# CountyDescription Property

Description of county (Russia)

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property CountyDescription As String
    Get
    Set
'Usage
Dim instance As IAddressV4
Dim value As String

value = instance.CountyDescription

instance.CountyDescription = value
```

``` csharp
string CountyDescription { get; set; }
```

``` c++
property String^ CountyDescription {
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


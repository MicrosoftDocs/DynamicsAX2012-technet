---
title: IAddressV2.CountryOKSMCode Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: CountryOKSMCode Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IAddressV2.CountryOKSMCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iaddressv2.countryoksmcode(v=AX.60)
ms:contentKeyID: 49849824
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IAddressV2.CountryOKSMCode
dev_langs:
- CSharp
- C++
- VB
---

# CountryOKSMCode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Note: This API is now obsolete.**

Specific to Russia

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<ObsoleteAttribute("Used in AX only, do not use in POS")> _
Property CountryOKSMCode As String
    Get
    Set
'Usage
Dim instance As IAddressV2
Dim value As String

value = instance.CountryOKSMCode

instance.CountryOKSMCode = value
```

``` csharp
[ObsoleteAttribute("Used in AX only, do not use in POS")]
string CountryOKSMCode { get; set; }
```

``` c++
[ObsoleteAttribute(L"Used in AX only, do not use in POS")]
property String^ CountryOKSMCode {
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


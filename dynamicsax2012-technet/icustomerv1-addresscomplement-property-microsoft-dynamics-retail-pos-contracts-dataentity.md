---
title: ICustomerV1.AddressComplement Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: AddressComplement Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerV1.AddressComplement
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.icustomerv1.addresscomplement(v=AX.60)
ms:contentKeyID: 47128073
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerV1.AddressComplement
dev_langs:
- CSharp
- C++
- VB
---

# AddressComplement Property

Gets or sets the address complement.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property AddressComplement As String
    Get
    Set
'Usage
Dim instance As ICustomerV1
Dim value As String

value = instance.AddressComplement

instance.AddressComplement = value
```

``` csharp
string AddressComplement { get; set; }
```

``` c++
property String^ AddressComplement {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)) value.  

## Remarks

This is a Brazil specific address field

## See Also

#### Reference

[ICustomerV1 Interface](icustomerv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)


---
title: Address.ThreeLetterISORegionName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ThreeLetterISORegionName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.ThreeLetterISORegionName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.address.threeletterisoregionname(v=AX.60)
ms:contentKeyID: 49838534
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.ThreeLetterISORegionName
dev_langs:
- CSharp
- C++
- VB
---

# ThreeLetterISORegionName Property

Gets or sets the Country 3-digit ISO Code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("COUNTRYREGIONID")> _
<DataMemberAttribute> _
Public Property ThreeLetterISORegionName As String
    Get
    Set
'Usage
Dim instance As Address
Dim value As String

value = instance.ThreeLetterISORegionName

instance.ThreeLetterISORegionName = value
```

``` csharp
[ColumnAttribute("COUNTRYREGIONID")]
[DataMemberAttribute]
public string ThreeLetterISORegionName { get; set; }
```

``` c++
[ColumnAttribute(L"COUNTRYREGIONID")]
[DataMemberAttribute]
public:
property String^ ThreeLetterISORegionName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The Country3DigitISOCode.  

## See Also

#### Reference

[Address Class](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


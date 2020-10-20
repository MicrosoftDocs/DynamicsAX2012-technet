---
title: Address.TwoLetterISORegionName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TwoLetterISORegionName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.TwoLetterISORegionName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.address.twoletterisoregionname(v=AX.60)
ms:contentKeyID: 62211868
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.TwoLetterISORegionName
dev_langs:
- CSharp
- C++
- VB
---

# TwoLetterISORegionName Property

Gets or sets the Country 2-digit ISO Code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ISOCODE")> _
Public Property TwoLetterISORegionName As String
    Get
    Set
'Usage
Dim instance As Address
Dim value As String

value = instance.TwoLetterISORegionName

instance.TwoLetterISORegionName = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ISOCODE")]
public string TwoLetterISORegionName { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ISOCODE")]
public:
property String^ TwoLetterISORegionName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The Country2DigitISOCode.  

## See Also

#### Reference

[Address Class](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


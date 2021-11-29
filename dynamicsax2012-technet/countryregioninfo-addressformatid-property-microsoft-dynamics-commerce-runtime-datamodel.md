---
title: CountryRegionInfo.AddressFormatId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AddressFormatId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CountryRegionInfo.AddressFormatId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.countryregioninfo.addressformatid(v=AX.60)
ms:contentKeyID: 62214118
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CountryRegionInfo.AddressFormatId
dev_langs:
- CSharp
- C++
- VB
---

# AddressFormatId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the address format identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ADDRESSFORMATID")> _
<DataMemberAttribute> _
Public Property AddressFormatId As String
    Get
    Set
'Usage
Dim instance As CountryRegionInfo
Dim value As String

value = instance.AddressFormatId

instance.AddressFormatId = value
```

``` csharp
[ColumnAttribute("ADDRESSFORMATID")]
[DataMemberAttribute]
public string AddressFormatId { get; set; }
```

``` c++
[ColumnAttribute(L"ADDRESSFORMATID")]
[DataMemberAttribute]
public:
property String^ AddressFormatId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[CountryRegionInfo Class](countryregioninfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


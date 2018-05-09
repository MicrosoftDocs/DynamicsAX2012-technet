---
title: CountryRegionInfo.AddressFormatName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AddressFormatName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CountryRegionInfo.AddressFormatName
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.countryregioninfo.addressformatname(v=AX.60)
ms:contentKeyID: 62213319
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CountryRegionInfo.AddressFormatName
dev_langs:
- CSharp
- C++
- VB
---

# AddressFormatName Property

Gets or sets the address format name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ADDRESSFORMATNAME")> _
Public Property AddressFormatName As String
    Get
    Set
'Usage
Dim instance As CountryRegionInfo
Dim value As String

value = instance.AddressFormatName

instance.AddressFormatName = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ADDRESSFORMATNAME")]
public string AddressFormatName { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ADDRESSFORMATNAME")]
public:
property String^ AddressFormatName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[CountryRegionInfo Class](countryregioninfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


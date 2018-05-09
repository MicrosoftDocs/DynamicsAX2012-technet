---
title: CountryRegionInfo.AddressFormatLines Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AddressFormatLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CountryRegionInfo.AddressFormatLines
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.countryregioninfo.addressformatlines(v=AX.60)
ms:contentKeyID: 62211985
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CountryRegionInfo.AddressFormatLines
dev_langs:
- CSharp
- C++
- VB
---

# AddressFormatLines Property

Gets the address format lines.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property AddressFormatLines As IList(Of AddressFormattingInfo)
    Get
    Set
'Usage
Dim instance As CountryRegionInfo
Dim value As IList(Of AddressFormattingInfo)

value = instance.AddressFormatLines

instance.AddressFormatLines = value
```

``` csharp
[DataMemberAttribute]
public IList<AddressFormattingInfo> AddressFormatLines { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IList<AddressFormattingInfo^>^ AddressFormatLines {
    IList<AddressFormattingInfo^>^ get ();
    void set (IList<AddressFormattingInfo^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/en-us/library/5y536ey6\(v=ax.60\))\<[AddressFormattingInfo](addressformattinginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IList\<T\>](https://technet.microsoft.com/en-us/library/5y536ey6\(v=ax.60\)).  

## See Also

#### Reference

[CountryRegionInfo Class](countryregioninfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


---
title: AddressSqliteDatabaseAccessor.GetCountryRegions Method  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite)
TOCTitle: GetCountryRegions Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.AddressSqliteDatabaseAccessor.GetCountryRegions(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.sqlite.addresssqlitedatabaseaccessor.getcountryregions(v=AX.60)
ms:contentKeyID: 65320326
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.AddressSqliteDatabaseAccessor.GetCountryRegions
dev_langs:
- CSharp
- C++
- VB
---

# GetCountryRegions Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite](microsoft-dynamics-commerce-runtime-dataservices-sqlite-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.dll)

## Syntax

``` vb
'Declaration
Public Function GetCountryRegions ( _
    languageId As String _
) As Tuple(Of ReadOnlyCollection(Of CountryRegionInfo), ReadOnlyCollection(Of AddressFormattingInfo))
'Usage
Dim instance As AddressSqliteDatabaseAccessor
Dim languageId As String
Dim returnValue As Tuple(Of ReadOnlyCollection(Of CountryRegionInfo), ReadOnlyCollection(Of AddressFormattingInfo))

returnValue = instance.GetCountryRegions(languageId)
```

``` csharp
public Tuple<ReadOnlyCollection<CountryRegionInfo>, ReadOnlyCollection<AddressFormattingInfo>> GetCountryRegions(
    string languageId
)
```

``` c++
public:
Tuple<ReadOnlyCollection<CountryRegionInfo^>^, ReadOnlyCollection<AddressFormattingInfo^>^>^ GetCountryRegions(
    String^ languageId
)
```

#### Parameters

  - languageId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: Tuple\<[ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[CountryRegionInfo](countryregioninfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>, [ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[AddressFormattingInfo](addressformattinginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>\>  

## See Also

#### Reference

[AddressSqliteDatabaseAccessor Class](addresssqlitedatabaseaccessor-class-microsoft-dynamics-commerce-runtime-dataservices-sqlite.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite Namespace](microsoft-dynamics-commerce-runtime-dataservices-sqlite-namespace.md)


---
title: CountryInfoResponse.Countries Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: Countries Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.CountryInfoResponse.Countries
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.services.countryinforesponse.countries(v=AX.60)
ms:contentKeyID: 65318438
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.CountryInfoResponse.Countries
dev_langs:
- CSharp
- C++
- VB
---

# Countries Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Countries As IEnumerable(Of CountryInfo)
    Get
    Friend Set
'Usage
Dim instance As CountryInfoResponse
Dim value As IEnumerable(Of CountryInfo)

value = instance.Countries
```

``` csharp
[DataMemberAttribute]
public IEnumerable<CountryInfo> Countries { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<CountryInfo^>^ Countries {
    IEnumerable<CountryInfo^>^ get ();
    internal: void set (IEnumerable<CountryInfo^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[CountryInfo](countryinfo-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[CountryInfoResponse Class](countryinforesponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)


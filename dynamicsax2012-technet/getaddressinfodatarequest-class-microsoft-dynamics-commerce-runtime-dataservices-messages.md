---
title: GetAddressInfoDataRequest Class (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetAddressInfoDataRequest Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetAddressInfoDataRequest
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getaddressinfodatarequest(v=AX.60)
ms:contentKeyID: 65319484
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetAddressInfoDataRequest
dev_langs:
- CSharp
- C++
- VB
---

# GetAddressInfoDataRequest Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The data service request to get address information.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public MustInherit Class GetAddressInfoDataRequest _
    Inherits DataRequest
'Usage
Dim instance As GetAddressInfoDataRequest
```

``` csharp
[DataContractAttribute]
public abstract class GetAddressInfoDataRequest : DataRequest
```

``` c++
[DataContractAttribute]
public ref class GetAddressInfoDataRequest abstract : public DataRequest
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Messages.Request](request-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.DataRequest](datarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetAddressInfoDataRequest  
        [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetAddressFormattingDataRequest](getaddressformattingdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
        [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetCitiesDataRequest](getcitiesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
        [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetCountiesDataRequest](getcountiesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
        [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetCountryRegionDataRequest](getcountryregiondatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
        [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetDistrictsDataRequest](getdistrictsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
        [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetFromZipPostalCodeDataRequest](getfromzippostalcodedatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
        [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetStateProvincesDataRequest](getstateprovincesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
        [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetSupportedLanguagesDataRequest](getsupportedlanguagesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
        [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetZipPostalCodeDataRequest](getzippostalcodedatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
        [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ValidateAddressDataRequest](validateaddressdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


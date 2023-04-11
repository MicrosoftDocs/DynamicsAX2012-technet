---
title: GetDistrictsDataRequest Class (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetDistrictsDataRequest Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetDistrictsDataRequest
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getdistrictsdatarequest(v=AX.60)
ms:contentKeyID: 65322391
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetDistrictsDataRequest
dev_langs:
- CSharp
- C++
- VB
---

# GetDistrictsDataRequest Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The data service request to get district information.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Class GetDistrictsDataRequest _
    Inherits GetAddressInfoDataRequest
'Usage
Dim instance As GetDistrictsDataRequest
```

``` csharp
[DataContractAttribute]
public class GetDistrictsDataRequest : GetAddressInfoDataRequest
```

``` c++
[DataContractAttribute]
public ref class GetDistrictsDataRequest : public GetAddressInfoDataRequest
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Messages.Request](request-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.DataRequest](datarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetAddressInfoDataRequest](getaddressinfodatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
        Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetDistrictsDataRequest  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


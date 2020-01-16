---
title: GetProductPricesServiceRequest Class (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetProductPricesServiceRequest Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetProductPricesServiceRequest
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getproductpricesservicerequest(v=AX.60)
ms:contentKeyID: 62213163
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetProductPricesServiceRequest
dev_langs:
- CSharp
- C++
- VB
---

# GetProductPricesServiceRequest Class

Gets the request to retrieve and update prices for the given products.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public NotInheritable Class GetProductPricesServiceRequest _
    Inherits ServiceRequest
'Usage
Dim instance As GetProductPricesServiceRequest
```

``` csharp
[DataContractAttribute]
public sealed class GetProductPricesServiceRequest : ServiceRequest
```

``` c++
[DataContractAttribute]
public ref class GetProductPricesServiceRequest sealed : public ServiceRequest
```

## Remarks

This also updates the RetailListingPrice table in the database for the given products.

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Messages.Request](request-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ServiceRequest](servicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)  
      Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetProductPricesServiceRequest  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


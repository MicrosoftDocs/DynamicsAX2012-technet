---
title: GetChangedPricesServiceResponse Class (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetChangedPricesServiceResponse Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetChangedPricesServiceResponse
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getchangedpricesserviceresponse(v=AX.60)
ms:contentKeyID: 62208221
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetChangedPricesServiceResponse
dev_langs:
- CSharp
- C++
- VB
---

# GetChangedPricesServiceResponse Class

Get the request to retrieve all listings that may have changed price since last call to this request.

Returned listings will have updated prices on them and the RetailListingPrice table is updated in the database.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public NotInheritable Class GetChangedPricesServiceResponse _
    Inherits Response
'Usage
Dim instance As GetChangedPricesServiceResponse
```

``` csharp
[DataContractAttribute]
public sealed class GetChangedPricesServiceResponse : Response
```

``` c++
[DataContractAttribute]
public ref class GetChangedPricesServiceResponse sealed : public Response
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Messages.Response](response-class-microsoft-dynamics-commerce-runtime-messages.md)  
    Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetChangedPricesServiceResponse  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


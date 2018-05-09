---
title: ICustomerService.GetAddresses Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: GetAddresses Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ICustomerService.GetAddresses
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.services.icustomerservice.getaddresses(v=AX.60)
ms:contentKeyID: 65317974
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ICustomerService.GetAddresses
dev_langs:
- CSharp
- C++
- VB
---

# GetAddresses Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function GetAddresses As AddressCollectionResponse
'Usage
Dim instance As ICustomerService
Dim returnValue As AddressCollectionResponse

returnValue = instance.GetAddresses()
```

``` csharp
[OperationContractAttribute]
AddressCollectionResponse GetAddresses()
```

``` c++
[OperationContractAttribute]
AddressCollectionResponse^ GetAddresses()
```

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.AddressCollectionResponse](addresscollectionresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[ICustomerService Interface](icustomerservice-interface-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)


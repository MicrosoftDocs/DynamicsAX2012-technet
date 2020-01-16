---
title: IChannelService.GetStateProvinceInfo Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: GetStateProvinceInfo Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.IChannelService.GetStateProvinceInfo(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.ichannelservice.getstateprovinceinfo(v=AX.60)
ms:contentKeyID: 65316213
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.IChannelService.GetStateProvinceInfo
dev_langs:
- CSharp
- C++
- VB
---

# GetStateProvinceInfo Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function GetStateProvinceInfo ( _
    countryCode As String _
) As StateProvinceInfoResponse
'Usage
Dim instance As IChannelService
Dim countryCode As String
Dim returnValue As StateProvinceInfoResponse

returnValue = instance.GetStateProvinceInfo(countryCode)
```

``` csharp
[OperationContractAttribute]
StateProvinceInfoResponse GetStateProvinceInfo(
    string countryCode
)
```

``` c++
[OperationContractAttribute]
StateProvinceInfoResponse^ GetStateProvinceInfo(
    String^ countryCode
)
```

#### Parameters

  - countryCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.StateProvinceInfoResponse](stateprovinceinforesponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[IChannelService Interface](ichannelservice-interface-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)


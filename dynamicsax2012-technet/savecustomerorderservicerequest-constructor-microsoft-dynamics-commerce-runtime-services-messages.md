---
title: SaveCustomerOrderServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: SaveCustomerOrderServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveCustomerOrderServiceRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction,Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration,Microsoft.Dynamics.Commerce.Runtime.DataModel.CardTokenInfo,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.savecustomerorderservicerequest.savecustomerorderservicerequest(v=AX.60)
ms:contentKeyID: 65319378
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveCustomerOrderServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# SaveCustomerOrderServiceRequest Constructor

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    salesTransaction As SalesTransaction, _
    channelConfiguration As ChannelConfiguration, _
    cardTokenInfo As CardTokenInfo, _
    cardAuthorizationTokenResponseXml As String _
)
'Usage
Dim salesTransaction As SalesTransaction
Dim channelConfiguration As ChannelConfiguration
Dim cardTokenInfo As CardTokenInfo
Dim cardAuthorizationTokenResponseXml As String

Dim instance As New SaveCustomerOrderServiceRequest(salesTransaction, _
    channelConfiguration, cardTokenInfo, _
    cardAuthorizationTokenResponseXml)
```

``` csharp
public SaveCustomerOrderServiceRequest(
    SalesTransaction salesTransaction,
    ChannelConfiguration channelConfiguration,
    CardTokenInfo cardTokenInfo,
    string cardAuthorizationTokenResponseXml
)
```

``` c++
public:
SaveCustomerOrderServiceRequest(
    SalesTransaction^ salesTransaction, 
    ChannelConfiguration^ channelConfiguration, 
    CardTokenInfo^ cardTokenInfo, 
    String^ cardAuthorizationTokenResponseXml
)
```

#### Parameters

  - salesTransaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - channelConfiguration  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration](channelconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - cardTokenInfo  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CardTokenInfo](cardtokeninfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - cardAuthorizationTokenResponseXml  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[SaveCustomerOrderServiceRequest Class](savecustomerorderservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


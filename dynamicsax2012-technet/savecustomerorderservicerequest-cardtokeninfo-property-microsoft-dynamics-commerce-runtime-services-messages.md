---
title: SaveCustomerOrderServiceRequest.CardTokenInfo Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: CardTokenInfo Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveCustomerOrderServiceRequest.CardTokenInfo
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.savecustomerorderservicerequest.cardtokeninfo(v=AX.60)
ms:contentKeyID: 65320665
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveCustomerOrderServiceRequest.CardTokenInfo
dev_langs:
- CSharp
- C++
- VB
---

# CardTokenInfo Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CardTokenInfo As CardTokenInfo
    Get
    Set
'Usage
Dim instance As SaveCustomerOrderServiceRequest
Dim value As CardTokenInfo

value = instance.CardTokenInfo

instance.CardTokenInfo = value
```

``` csharp
[DataMemberAttribute]
public CardTokenInfo CardTokenInfo { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property CardTokenInfo^ CardTokenInfo {
    CardTokenInfo^ get ();
    void set (CardTokenInfo^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CardTokenInfo](cardtokeninfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[SaveCustomerOrderServiceRequest Class](savecustomerorderservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


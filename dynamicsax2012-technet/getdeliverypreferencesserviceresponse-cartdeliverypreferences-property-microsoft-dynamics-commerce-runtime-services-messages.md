---
title: GetDeliveryPreferencesServiceResponse.CartDeliveryPreferences Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: CartDeliveryPreferences Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetDeliveryPreferencesServiceResponse.CartDeliveryPreferences
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getdeliverypreferencesserviceresponse.cartdeliverypreferences(v=AX.60)
ms:contentKeyID: 65319370
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetDeliveryPreferencesServiceResponse.CartDeliveryPreferences
dev_langs:
- CSharp
- C++
- VB
---

# CartDeliveryPreferences Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CartDeliveryPreferences As CartDeliveryPreferences
    Get
    Private Set
'Usage
Dim instance As GetDeliveryPreferencesServiceResponse
Dim value As CartDeliveryPreferences

value = instance.CartDeliveryPreferences
```

``` csharp
[DataMemberAttribute]
public CartDeliveryPreferences CartDeliveryPreferences { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property CartDeliveryPreferences^ CartDeliveryPreferences {
    CartDeliveryPreferences^ get ();
    private: void set (CartDeliveryPreferences^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CartDeliveryPreferences](cartdeliverypreferences-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetDeliveryPreferencesServiceResponse Class](getdeliverypreferencesserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


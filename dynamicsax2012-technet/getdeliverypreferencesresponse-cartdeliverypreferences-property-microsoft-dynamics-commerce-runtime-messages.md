---
title: GetDeliveryPreferencesResponse.CartDeliveryPreferences Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: CartDeliveryPreferences Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetDeliveryPreferencesResponse.CartDeliveryPreferences
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getdeliverypreferencesresponse.cartdeliverypreferences(v=AX.60)
ms:contentKeyID: 65317963
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetDeliveryPreferencesResponse.CartDeliveryPreferences
dev_langs:
- CSharp
- C++
- VB
---

# CartDeliveryPreferences Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CartDeliveryPreferences As CartDeliveryPreferences
    Get
    Private Set
'Usage
Dim instance As GetDeliveryPreferencesResponse
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

[GetDeliveryPreferencesResponse Class](getdeliverypreferencesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


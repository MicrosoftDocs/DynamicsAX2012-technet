---
title: GetAllDeliveryOptionsResponse.DeliveryOptions Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: DeliveryOptions Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetAllDeliveryOptionsResponse.DeliveryOptions
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getalldeliveryoptionsresponse.deliveryoptions(v=AX.60)
ms:contentKeyID: 62211450
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetAllDeliveryOptionsResponse.DeliveryOptions
dev_langs:
- CSharp
- C++
- VB
---

# DeliveryOptions Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of delivery options that have been computed for the entire cart.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DeliveryOptions As ReadOnlyCollection(Of DeliveryOption)
    Get
    Private Set
'Usage
Dim instance As GetAllDeliveryOptionsResponse
Dim value As ReadOnlyCollection(Of DeliveryOption)

value = instance.DeliveryOptions
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<DeliveryOption> DeliveryOptions { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<DeliveryOption^>^ DeliveryOptions {
    ReadOnlyCollection<DeliveryOption^>^ get ();
    private: void set (ReadOnlyCollection<DeliveryOption^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[DeliveryOption](deliveryoption-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetAllDeliveryOptionsResponse Class](getalldeliveryoptionsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


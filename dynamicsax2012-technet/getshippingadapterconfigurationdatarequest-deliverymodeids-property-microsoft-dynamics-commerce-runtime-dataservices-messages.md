---
title: GetShippingAdapterConfigurationDataRequest.DeliveryModeIds Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: DeliveryModeIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetShippingAdapterConfigurationDataRequest.DeliveryModeIds
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getshippingadapterconfigurationdatarequest.deliverymodeids(v=AX.60)
ms:contentKeyID: 65320662
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetShippingAdapterConfigurationDataRequest.DeliveryModeIds
dev_langs:
- CSharp
- C++
- VB
---

# DeliveryModeIds Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the delivery mode identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DeliveryModeIds As IEnumerable(Of String)
    Get
    Private Set
'Usage
Dim instance As GetShippingAdapterConfigurationDataRequest
Dim value As IEnumerable(Of String)

value = instance.DeliveryModeIds
```

``` csharp
[DataMemberAttribute]
public IEnumerable<string> DeliveryModeIds { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<String^>^ DeliveryModeIds {
    IEnumerable<String^>^ get ();
    private: void set (IEnumerable<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[GetShippingAdapterConfigurationDataRequest Class](getshippingadapterconfigurationdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


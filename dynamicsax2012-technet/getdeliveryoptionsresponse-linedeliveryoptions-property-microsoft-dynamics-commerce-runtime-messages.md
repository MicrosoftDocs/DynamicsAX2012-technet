---
title: GetDeliveryOptionsResponse.LineDeliveryOptions Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: LineDeliveryOptions Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetDeliveryOptionsResponse.LineDeliveryOptions
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getdeliveryoptionsresponse.linedeliveryoptions(v=AX.60)
ms:contentKeyID: 49853065
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetDeliveryOptionsResponse.LineDeliveryOptions
dev_langs:
- CSharp
- C++
- VB
---

# LineDeliveryOptions Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of delivery options that have been computed at line level.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LineDeliveryOptions As ReadOnlyCollection(Of SalesLineDeliveryOption)
    Get
    Private Set
'Usage
Dim instance As GetDeliveryOptionsResponse
Dim value As ReadOnlyCollection(Of SalesLineDeliveryOption)

value = instance.LineDeliveryOptions
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<SalesLineDeliveryOption> LineDeliveryOptions { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<SalesLineDeliveryOption^>^ LineDeliveryOptions {
    ReadOnlyCollection<SalesLineDeliveryOption^>^ get ();
    private: void set (ReadOnlyCollection<SalesLineDeliveryOption^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[SalesLineDeliveryOption](saleslinedeliveryoption-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetDeliveryOptionsResponse Class](getdeliveryoptionsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


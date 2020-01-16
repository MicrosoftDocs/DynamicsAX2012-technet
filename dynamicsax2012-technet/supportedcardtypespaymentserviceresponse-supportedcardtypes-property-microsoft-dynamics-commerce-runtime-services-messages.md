---
title: SupportedCardTypesPaymentServiceResponse.SupportedCardTypes Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: SupportedCardTypes Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SupportedCardTypesPaymentServiceResponse.SupportedCardTypes
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.supportedcardtypespaymentserviceresponse.supportedcardtypes(v=AX.60)
ms:contentKeyID: 62208282
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SupportedCardTypesPaymentServiceResponse.SupportedCardTypes
dev_langs:
- CSharp
- C++
- VB
---

# SupportedCardTypes Property

Gets the supported card types for the connectors.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SupportedCardTypes As ReadOnlyCollection(Of String)
    Get
    Private Set
'Usage
Dim instance As SupportedCardTypesPaymentServiceResponse
Dim value As ReadOnlyCollection(Of String)

value = instance.SupportedCardTypes
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<string> SupportedCardTypes { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<String^>^ SupportedCardTypes {
    ReadOnlyCollection<String^>^ get ();
    private: void set (ReadOnlyCollection<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[SupportedCardTypesPaymentServiceResponse Class](supportedcardtypespaymentserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


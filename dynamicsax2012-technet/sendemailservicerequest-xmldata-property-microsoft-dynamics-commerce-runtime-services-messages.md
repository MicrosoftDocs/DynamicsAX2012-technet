---
title: SendEmailServiceRequest.XmlData Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: XmlData Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SendEmailServiceRequest.XmlData
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.sendemailservicerequest.xmldata(v=AX.60)
ms:contentKeyID: 49854424
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SendEmailServiceRequest.XmlData
dev_langs:
- CSharp
- C++
- VB
---

# XmlData Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the XML data used in the XSLT transform of the message.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property XmlData As Object
    Get
    Private Set
'Usage
Dim instance As SendEmailServiceRequest
Dim value As Object

value = instance.XmlData
```

``` csharp
[DataMemberAttribute]
public Object XmlData { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Object^ XmlData {
    Object^ get ();
    private: void set (Object^ value);
}
```

#### Property Value

Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
Returns [Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\)).  

## See Also

#### Reference

[SendEmailServiceRequest Class](sendemailservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


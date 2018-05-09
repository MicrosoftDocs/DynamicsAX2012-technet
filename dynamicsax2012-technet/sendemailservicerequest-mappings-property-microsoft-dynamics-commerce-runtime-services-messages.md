---
title: SendEmailServiceRequest.Mappings Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Mappings Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SendEmailServiceRequest.Mappings
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.sendemailservicerequest.mappings(v=AX.60)
ms:contentKeyID: 49839978
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SendEmailServiceRequest.Mappings
dev_langs:
- CSharp
- C++
- VB
---

# Mappings Property

Gets the collection of name/value pairs to be used in the the token replacement of the message.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Mappings As ICollection(Of NameValuePair)
    Get
    Private Set
'Usage
Dim instance As SendEmailServiceRequest
Dim value As ICollection(Of NameValuePair)

value = instance.Mappings
```

``` csharp
[DataMemberAttribute]
public ICollection<NameValuePair> Mappings { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<NameValuePair^>^ Mappings {
    ICollection<NameValuePair^>^ get ();
    private: void set (ICollection<NameValuePair^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/en-us/library/92t2ye13\(v=ax.60\))\<[NameValuePair](namevaluepair-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ICollection\<T\>](https://technet.microsoft.com/en-us/library/92t2ye13\(v=ax.60\)).  

## See Also

#### Reference

[SendEmailServiceRequest Class](sendemailservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


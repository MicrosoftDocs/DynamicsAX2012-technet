---
title: SendCustomerEmailRequest.EmailTemplateProperties Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: EmailTemplateProperties Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.SendCustomerEmailRequest.EmailTemplateProperties
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.sendcustomeremailrequest.emailtemplateproperties(v=AX.60)
ms:contentKeyID: 49849842
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.SendCustomerEmailRequest.EmailTemplateProperties
dev_langs:
- CSharp
- C++
- VB
---

# EmailTemplateProperties Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the e-mail template properties.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property EmailTemplateProperties As ICollection(Of NameValuePair)
    Get
    Private Set
'Usage
Dim instance As SendCustomerEmailRequest
Dim value As ICollection(Of NameValuePair)

value = instance.EmailTemplateProperties
```

``` csharp
[DataMemberAttribute]
public ICollection<NameValuePair> EmailTemplateProperties { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<NameValuePair^>^ EmailTemplateProperties {
    ICollection<NameValuePair^>^ get ();
    private: void set (ICollection<NameValuePair^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[NameValuePair](namevaluepair-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The e-mail template properties.  

## See Also

#### Reference

[SendCustomerEmailRequest Class](sendcustomeremailrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


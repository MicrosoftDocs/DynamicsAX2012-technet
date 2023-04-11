---
title: ValidateAccountActivationDataResponse.IsRequestValid Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: IsRequestValid Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ValidateAccountActivationDataResponse.IsRequestValid
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.validateaccountactivationdataresponse.isrequestvalid(v=AX.60)
ms:contentKeyID: 65323066
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ValidateAccountActivationDataResponse.IsRequestValid
dev_langs:
- CSharp
- C++
- VB
---

# IsRequestValid Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether customer account activation request is valid.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsRequestValid As Boolean
    Get
    Private Set
'Usage
Dim instance As ValidateAccountActivationDataResponse
Dim value As Boolean

value = instance.IsRequestValid
```

``` csharp
[DataMemberAttribute]
public bool IsRequestValid { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsRequestValid {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
The indicator of whether customer account activation request is valid.  

## See Also

#### Reference

[ValidateAccountActivationDataResponse Class](validateaccountactivationdataresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


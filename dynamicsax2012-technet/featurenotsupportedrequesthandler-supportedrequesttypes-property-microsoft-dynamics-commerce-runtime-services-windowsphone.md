---
title: FeatureNotSupportedRequestHandler.SupportedRequestTypes Property  (Microsoft.Dynamics.Commerce.Runtime.Services.WindowsPhone)
TOCTitle: SupportedRequestTypes Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.WindowsPhone.FeatureNotSupportedRequestHandler.SupportedRequestTypes
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.windowsphone.featurenotsupportedrequesthandler.supportedrequesttypes(v=AX.60)
ms:contentKeyID: 65321401
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.WindowsPhone.FeatureNotSupportedRequestHandler.SupportedRequestTypes
dev_langs:
- CSharp
- C++
- VB
---

# SupportedRequestTypes Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.WindowsPhone](microsoft-dynamics-commerce-runtime-services-windowsphone-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.WindowsPhone (in Microsoft.Dynamics.Commerce.Runtime.Services.WindowsPhone.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property SupportedRequestTypes As IEnumerable(Of Type)
    Get
'Usage
Dim instance As FeatureNotSupportedRequestHandler
Dim value As IEnumerable(Of Type)

value = instance.SupportedRequestTypes
```

``` csharp
public IEnumerable<Type> SupportedRequestTypes { get; }
```

``` c++
public:
virtual property IEnumerable<Type^>^ SupportedRequestTypes {
    IEnumerable<Type^>^ get () sealed;
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[Type](https://technet.microsoft.com/en-us/library/42892f65\(v=ax.60\))\>  

#### Implements

[IRequestHandler.SupportedRequestTypes](irequesthandler-supportedrequesttypes-property-microsoft-dynamics-commerce-runtime-workflow.md)  

## See Also

#### Reference

[FeatureNotSupportedRequestHandler Class](featurenotsupportedrequesthandler-class-microsoft-dynamics-commerce-runtime-services-windowsphone.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.WindowsPhone Namespace](microsoft-dynamics-commerce-runtime-services-windowsphone-namespace.md)


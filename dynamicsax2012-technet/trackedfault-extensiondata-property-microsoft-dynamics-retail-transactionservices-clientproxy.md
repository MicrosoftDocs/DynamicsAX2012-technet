---
title: TrackedFault.ExtensionData Property  (Microsoft.Dynamics.Retail.TransactionServices.ClientProxy)
TOCTitle: ExtensionData Property
ms:assetid: P:Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.TrackedFault.ExtensionData
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.transactionservices.clientproxy.trackedfault.extensiondata(v=AX.60)
ms:contentKeyID: 49837027
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.TransactionServices.ClientProxy.TrackedFault.ExtensionData
dev_langs:
- CSharp
- C++
- VB
---

# ExtensionData Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.TransactionServices.ClientProxy](microsoft-dynamics-retail-transactionservices-clientproxy-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property ExtensionData As ExtensionDataObject
    Get
    Set
'Usage
Dim instance As TrackedFault
Dim value As ExtensionDataObject

value = instance.ExtensionData

instance.ExtensionData = value
```

``` csharp
public ExtensionDataObject ExtensionData { get; set; }
```

``` c++
public:
virtual property ExtensionDataObject^ ExtensionData {
    ExtensionDataObject^ get () sealed;
    void set (ExtensionDataObject^ value) sealed;
}
```

#### Property Value

Type: [System.Runtime.Serialization.ExtensionDataObject](https://technet.microsoft.com/library/ms574816\(v=ax.60\))  
Returns [ExtensionDataObject](https://technet.microsoft.com/library/ms574816\(v=ax.60\)).  

#### Implements

[IExtensibleDataObject.ExtensionData](https://technet.microsoft.com/library/ms553662\(v=ax.60\))  

## See Also

#### Reference

[TrackedFault Class](trackedfault-class-microsoft-dynamics-retail-transactionservices-clientproxy.md)

[Microsoft.Dynamics.Retail.TransactionServices.ClientProxy Namespace](microsoft-dynamics-retail-transactionservices-clientproxy-namespace.md)


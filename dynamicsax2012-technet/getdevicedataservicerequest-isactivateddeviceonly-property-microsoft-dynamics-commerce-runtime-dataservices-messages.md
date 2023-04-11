---
title: GetDeviceDataServiceRequest.IsActivatedDeviceOnly Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: IsActivatedDeviceOnly Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetDeviceDataServiceRequest.IsActivatedDeviceOnly
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getdevicedataservicerequest.isactivateddeviceonly(v=AX.60)
ms:contentKeyID: 65320468
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetDeviceDataServiceRequest.IsActivatedDeviceOnly
dev_langs:
- CSharp
- C++
- VB
---

# IsActivatedDeviceOnly Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether to get only the activated device.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsActivatedDeviceOnly As Boolean
    Get
    Private Set
'Usage
Dim instance As GetDeviceDataServiceRequest
Dim value As Boolean

value = instance.IsActivatedDeviceOnly
```

``` csharp
[DataMemberAttribute]
public bool IsActivatedDeviceOnly { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsActivatedDeviceOnly {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
The value indicating whether to get only the activated device.  

## See Also

#### Reference

[GetDeviceDataServiceRequest Class](getdevicedataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


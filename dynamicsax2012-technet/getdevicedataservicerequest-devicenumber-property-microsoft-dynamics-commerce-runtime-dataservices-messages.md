---
title: GetDeviceDataServiceRequest.DeviceNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: DeviceNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetDeviceDataServiceRequest.DeviceNumber
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getdevicedataservicerequest.devicenumber(v=AX.60)
ms:contentKeyID: 65320651
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetDeviceDataServiceRequest.DeviceNumber
dev_langs:
- CSharp
- C++
- VB
---

# DeviceNumber Property

Gets the device number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DeviceNumber As String
    Get
    Private Set
'Usage
Dim instance As GetDeviceDataServiceRequest
Dim value As String

value = instance.DeviceNumber
```

``` csharp
[DataMemberAttribute]
public string DeviceNumber { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ DeviceNumber {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The device number.  

## See Also

#### Reference

[GetDeviceDataServiceRequest Class](getdevicedataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


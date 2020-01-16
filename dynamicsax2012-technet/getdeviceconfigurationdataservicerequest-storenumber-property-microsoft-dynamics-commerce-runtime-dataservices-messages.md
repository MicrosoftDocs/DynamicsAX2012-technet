---
title: GetDeviceConfigurationDataServiceRequest.StoreNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: StoreNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetDeviceConfigurationDataServiceRequest.StoreNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getdeviceconfigurationdataservicerequest.storenumber(v=AX.60)
ms:contentKeyID: 65322013
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetDeviceConfigurationDataServiceRequest.StoreNumber
dev_langs:
- CSharp
- C++
- VB
---

# StoreNumber Property

Gets the store number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property StoreNumber As String
    Get
    Private Set
'Usage
Dim instance As GetDeviceConfigurationDataServiceRequest
Dim value As String

value = instance.StoreNumber
```

``` csharp
[DataMemberAttribute]
public string StoreNumber { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ StoreNumber {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetDeviceConfigurationDataServiceRequest Class](getdeviceconfigurationdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


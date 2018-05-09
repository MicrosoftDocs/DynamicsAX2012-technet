---
title: ValidateAddressDataResponse.InvalidAddressComponentName Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: InvalidAddressComponentName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ValidateAddressDataResponse.InvalidAddressComponentName
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.validateaddressdataresponse.invalidaddresscomponentname(v=AX.60)
ms:contentKeyID: 65318251
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ValidateAddressDataResponse.InvalidAddressComponentName
dev_langs:
- CSharp
- C++
- VB
---

# InvalidAddressComponentName Property

Gets the name of the invalid address component.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property InvalidAddressComponentName As String
    Get
    Private Set
'Usage
Dim instance As ValidateAddressDataResponse
Dim value As String

value = instance.InvalidAddressComponentName
```

``` csharp
[DataMemberAttribute]
public string InvalidAddressComponentName { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ InvalidAddressComponentName {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ValidateAddressDataResponse Class](validateaddressdataresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


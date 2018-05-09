---
title: ValidateAddressDataResponse Constructor (Boolean, String, String) (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: ValidateAddressDataResponse Constructor (Boolean, String, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ValidateAddressDataResponse.#ctor(System.Boolean,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.validateaddressdataresponse.validateaddressdataresponse(v=AX.60)
ms:contentKeyID: 65322898
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ValidateAddressDataResponse Constructor (Boolean, String, String)

Initializes a new instance of the [ValidateAddressDataResponse](validateaddressdataresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    isAddressValid As Boolean, _
    invalidAddressComponentName As String, _
    errorMessage As String _
)
'Usage
Dim isAddressValid As Boolean
Dim invalidAddressComponentName As String
Dim errorMessage As String

Dim instance As New ValidateAddressDataResponse(isAddressValid, _
    invalidAddressComponentName, errorMessage)
```

``` csharp
public ValidateAddressDataResponse(
    bool isAddressValid,
    string invalidAddressComponentName,
    string errorMessage
)
```

``` c++
public:
ValidateAddressDataResponse(
    bool isAddressValid, 
    String^ invalidAddressComponentName, 
    String^ errorMessage
)
```

#### Parameters

  - isAddressValid  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - invalidAddressComponentName  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - errorMessage  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ValidateAddressDataResponse Class](validateaddressdataresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[ValidateAddressDataResponse Overload](validateaddressdataresponse-constructor-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


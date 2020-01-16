---
title: ValidateAddressDataResponse.IsAddressValid Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: IsAddressValid Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ValidateAddressDataResponse.IsAddressValid
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.validateaddressdataresponse.isaddressvalid(v=AX.60)
ms:contentKeyID: 65316045
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ValidateAddressDataResponse.IsAddressValid
dev_langs:
- CSharp
- C++
- VB
---

# IsAddressValid Property

Gets a value indicating whether this instance is address valid.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsAddressValid As Boolean
    Get
    Private Set
'Usage
Dim instance As ValidateAddressDataResponse
Dim value As Boolean

value = instance.IsAddressValid
```

``` csharp
[DataMemberAttribute]
public bool IsAddressValid { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsAddressValid {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ValidateAddressDataResponse Class](validateaddressdataresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


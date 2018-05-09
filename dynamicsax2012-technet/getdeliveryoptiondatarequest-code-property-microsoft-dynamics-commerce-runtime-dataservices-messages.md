---
title: GetDeliveryOptionDataRequest.Code Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: Code Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetDeliveryOptionDataRequest.Code
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getdeliveryoptiondatarequest.code(v=AX.60)
ms:contentKeyID: 65320897
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetDeliveryOptionDataRequest.Code
dev_langs:
- CSharp
- C++
- VB
---

# Code Property

Gets the code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Code As String
    Get
    Private Set
'Usage
Dim instance As GetDeliveryOptionDataRequest
Dim value As String

value = instance.Code
```

``` csharp
[DataMemberAttribute]
public string Code { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Code {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The code.  

## See Also

#### Reference

[GetDeliveryOptionDataRequest Class](getdeliveryoptiondatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


---
title: GetCustomersRequest.CustomerPartyNumber Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: CustomerPartyNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetCustomersRequest.CustomerPartyNumber
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getcustomersrequest.customerpartynumber(v=AX.60)
ms:contentKeyID: 62202648
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetCustomersRequest.CustomerPartyNumber
dev_langs:
- CSharp
- C++
- VB
---

# CustomerPartyNumber Property

Gets or sets the customer party number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CustomerPartyNumber As String
    Get
    Set
'Usage
Dim instance As GetCustomersRequest
Dim value As String

value = instance.CustomerPartyNumber

instance.CustomerPartyNumber = value
```

``` csharp
[DataMemberAttribute]
public string CustomerPartyNumber { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ CustomerPartyNumber {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The customer party number.  

## See Also

#### Reference

[GetCustomersRequest Class](getcustomersrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


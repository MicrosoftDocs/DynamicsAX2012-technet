---
title: GetCustomerWithPartyNumberDataRequest.PartyNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: PartyNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetCustomerWithPartyNumberDataRequest.PartyNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getcustomerwithpartynumberdatarequest.partynumber(v=AX.60)
ms:contentKeyID: 65316292
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetCustomerWithPartyNumberDataRequest.PartyNumber
dev_langs:
- CSharp
- C++
- VB
---

# PartyNumber Property

Gets the party number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PartyNumber As String
    Get
    Private Set
'Usage
Dim instance As GetCustomerWithPartyNumberDataRequest
Dim value As String

value = instance.PartyNumber
```

``` csharp
[DataMemberAttribute]
public string PartyNumber { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ PartyNumber {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The party number.  

## See Also

#### Reference

[GetCustomerWithPartyNumberDataRequest Class](getcustomerwithpartynumberdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


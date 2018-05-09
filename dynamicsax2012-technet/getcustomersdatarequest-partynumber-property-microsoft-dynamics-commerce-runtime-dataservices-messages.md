---
title: GetCustomersDataRequest.PartyNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: PartyNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetCustomersDataRequest.PartyNumber
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getcustomersdatarequest.partynumber(v=AX.60)
ms:contentKeyID: 65319959
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetCustomersDataRequest.PartyNumber
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
Dim instance As GetCustomersDataRequest
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

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The party number.  

## See Also

#### Reference

[GetCustomersDataRequest Class](getcustomersdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


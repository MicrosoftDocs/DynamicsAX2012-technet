---
title: GetNextReceiptIdServiceResponse.NextReceiptId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: NextReceiptId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetNextReceiptIdServiceResponse.NextReceiptId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getnextreceiptidserviceresponse.nextreceiptid(v=AX.60)
ms:contentKeyID: 62210584
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetNextReceiptIdServiceResponse.NextReceiptId
dev_langs:
- CSharp
- C++
- VB
---

# NextReceiptId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the next receipt identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property NextReceiptId As String
    Get
    Private Set
'Usage
Dim instance As GetNextReceiptIdServiceResponse
Dim value As String

value = instance.NextReceiptId
```

``` csharp
[DataMemberAttribute]
public string NextReceiptId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ NextReceiptId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetNextReceiptIdServiceResponse Class](getnextreceiptidserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


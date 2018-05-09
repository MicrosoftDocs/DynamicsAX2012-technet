---
title: CreditMemoRealtimeRequestBase.ReceiptId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ReceiptId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CreditMemoRealtimeRequestBase.ReceiptId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.creditmemorealtimerequestbase.receiptid(v=AX.60)
ms:contentKeyID: 65322254
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CreditMemoRealtimeRequestBase.ReceiptId
dev_langs:
- CSharp
- C++
- VB
---

# ReceiptId Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ReceiptId As String
    Get
    Private Set
'Usage
Dim instance As CreditMemoRealtimeRequestBase
Dim value As String

value = instance.ReceiptId
```

``` csharp
[DataMemberAttribute]
public string ReceiptId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ReceiptId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[CreditMemoRealtimeRequestBase Class](creditmemorealtimerequestbase-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


---
title: GetCreditMemoServiceRequest.CreditMemoId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: CreditMemoId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCreditMemoServiceRequest.CreditMemoId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getcreditmemoservicerequest.creditmemoid(v=AX.60)
ms:contentKeyID: 65320684
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCreditMemoServiceRequest.CreditMemoId
dev_langs:
- CSharp
- C++
- VB
---

# CreditMemoId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CreditMemoId As String
    Get
    Private Set
'Usage
Dim instance As GetCreditMemoServiceRequest
Dim value As String

value = instance.CreditMemoId
```

``` csharp
[DataMemberAttribute]
public string CreditMemoId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ CreditMemoId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[GetCreditMemoServiceRequest Class](getcreditmemoservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


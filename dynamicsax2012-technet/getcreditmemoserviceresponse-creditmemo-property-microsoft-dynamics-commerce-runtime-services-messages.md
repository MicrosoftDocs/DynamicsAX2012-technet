---
title: GetCreditMemoServiceResponse.CreditMemo Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: CreditMemo Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCreditMemoServiceResponse.CreditMemo
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getcreditmemoserviceresponse.creditmemo(v=AX.60)
ms:contentKeyID: 62204362
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCreditMemoServiceResponse.CreditMemo
dev_langs:
- CSharp
- C++
- VB
---

# CreditMemo Property

Gets the gift card.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CreditMemo As CreditMemo
    Get
    Private Set
'Usage
Dim instance As GetCreditMemoServiceResponse
Dim value As CreditMemo

value = instance.CreditMemo
```

``` csharp
[DataMemberAttribute]
public CreditMemo CreditMemo { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property CreditMemo^ CreditMemo {
    CreditMemo^ get ();
    private: void set (CreditMemo^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CreditMemo](creditmemo-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [CreditMemo](creditmemo-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetCreditMemoServiceResponse Class](getcreditmemoserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


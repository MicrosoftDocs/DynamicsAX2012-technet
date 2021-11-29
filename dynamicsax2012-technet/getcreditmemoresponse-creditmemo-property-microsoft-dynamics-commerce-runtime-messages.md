---
title: GetCreditMemoResponse.CreditMemo Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: CreditMemo Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetCreditMemoResponse.CreditMemo
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getcreditmemoresponse.creditmemo(v=AX.60)
ms:contentKeyID: 62208663
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetCreditMemoResponse.CreditMemo
dev_langs:
- CSharp
- C++
- VB
---

# CreditMemo Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the credit memo.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CreditMemo As CreditMemo
    Get
    Private Set
'Usage
Dim instance As GetCreditMemoResponse
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

[GetCreditMemoResponse Class](getcreditmemoresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


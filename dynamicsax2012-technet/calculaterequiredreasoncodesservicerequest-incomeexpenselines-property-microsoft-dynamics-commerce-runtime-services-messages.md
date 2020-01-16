---
title: CalculateRequiredReasonCodesServiceRequest.IncomeExpenseLines Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: IncomeExpenseLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateRequiredReasonCodesServiceRequest.IncomeExpenseLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.calculaterequiredreasoncodesservicerequest.incomeexpenselines(v=AX.60)
ms:contentKeyID: 65317343
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateRequiredReasonCodesServiceRequest.IncomeExpenseLines
dev_langs:
- CSharp
- C++
- VB
---

# IncomeExpenseLines Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IncomeExpenseLines As IEnumerable(Of IncomeExpenseLine)
    Get
    Private Set
'Usage
Dim instance As CalculateRequiredReasonCodesServiceRequest
Dim value As IEnumerable(Of IncomeExpenseLine)

value = instance.IncomeExpenseLines
```

``` csharp
[DataMemberAttribute]
public IEnumerable<IncomeExpenseLine> IncomeExpenseLines { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<IncomeExpenseLine^>^ IncomeExpenseLines {
    IEnumerable<IncomeExpenseLine^>^ get ();
    private: void set (IEnumerable<IncomeExpenseLine^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[IncomeExpenseLine](incomeexpenseline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[CalculateRequiredReasonCodesServiceRequest Class](calculaterequiredreasoncodesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


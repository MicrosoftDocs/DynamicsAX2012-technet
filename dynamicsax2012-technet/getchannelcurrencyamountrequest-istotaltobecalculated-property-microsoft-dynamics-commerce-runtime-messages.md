---
title: GetChannelCurrencyAmountRequest.IsTotalToBeCalculated Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: IsTotalToBeCalculated Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelCurrencyAmountRequest.IsTotalToBeCalculated
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getchannelcurrencyamountrequest.istotaltobecalculated(v=AX.60)
ms:contentKeyID: 62204221
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelCurrencyAmountRequest.IsTotalToBeCalculated
dev_langs:
- CSharp
- C++
- VB
---

# IsTotalToBeCalculated Property

Gets or sets a value indicating whether to calculate total.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsTotalToBeCalculated As Boolean
    Get
    Set
'Usage
Dim instance As GetChannelCurrencyAmountRequest
Dim value As Boolean

value = instance.IsTotalToBeCalculated

instance.IsTotalToBeCalculated = value
```

``` csharp
[DataMemberAttribute]
public bool IsTotalToBeCalculated { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsTotalToBeCalculated {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[GetChannelCurrencyAmountRequest Class](getchannelcurrencyamountrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


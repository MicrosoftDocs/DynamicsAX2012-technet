---
title: GetChannelCurrencyAmountResponse.CurrencyAmounts Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: CurrencyAmounts Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelCurrencyAmountResponse.CurrencyAmounts
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getchannelcurrencyamountresponse.currencyamounts(v=AX.60)
ms:contentKeyID: 62213026
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelCurrencyAmountResponse.CurrencyAmounts
dev_langs:
- CSharp
- C++
- VB
---

# CurrencyAmounts Property

Gets the channel currency amount..

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CurrencyAmounts As ReadOnlyCollection(Of CurrencyAmount)
    Get
    Private Set
'Usage
Dim instance As GetChannelCurrencyAmountResponse
Dim value As ReadOnlyCollection(Of CurrencyAmount)

value = instance.CurrencyAmounts
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<CurrencyAmount> CurrencyAmounts { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<CurrencyAmount^>^ CurrencyAmounts {
    ReadOnlyCollection<CurrencyAmount^>^ get ();
    private: void set (ReadOnlyCollection<CurrencyAmount^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[CurrencyAmount](currencyamount-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetChannelCurrencyAmountResponse Class](getchannelcurrencyamountresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


---
title: GetCurrenciesResponse.Currencies Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Currencies Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetCurrenciesResponse.Currencies
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getcurrenciesresponse.currencies(v=AX.60)
ms:contentKeyID: 62205531
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetCurrenciesResponse.Currencies
dev_langs:
- CSharp
- C++
- VB
---

# Currencies Property

Gets the collection of currency.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Currencies As ReadOnlyCollection(Of Currency)
    Get
    Private Set
'Usage
Dim instance As GetCurrenciesResponse
Dim value As ReadOnlyCollection(Of Currency)

value = instance.Currencies
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<Currency> Currencies { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<Currency^>^ Currencies {
    ReadOnlyCollection<Currency^>^ get ();
    private: void set (ReadOnlyCollection<Currency^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[Currency](currency-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetCurrenciesResponse Class](getcurrenciesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


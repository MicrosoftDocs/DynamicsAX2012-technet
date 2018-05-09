---
title: GetAddressResponse.StateProvinces Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: StateProvinces Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetAddressResponse.StateProvinces
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getaddressresponse.stateprovinces(v=AX.60)
ms:contentKeyID: 62214499
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetAddressResponse.StateProvinces
dev_langs:
- CSharp
- C++
- VB
---

# StateProvinces Property

Gets the collection of state provinces.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property StateProvinces As ReadOnlyCollection(Of StateProvinceInfo)
    Get
    Private Set
'Usage
Dim instance As GetAddressResponse
Dim value As ReadOnlyCollection(Of StateProvinceInfo)

value = instance.StateProvinces
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<StateProvinceInfo> StateProvinces { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<StateProvinceInfo^>^ StateProvinces {
    ReadOnlyCollection<StateProvinceInfo^>^ get ();
    private: void set (ReadOnlyCollection<StateProvinceInfo^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[StateProvinceInfo](stateprovinceinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetAddressResponse Class](getaddressresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


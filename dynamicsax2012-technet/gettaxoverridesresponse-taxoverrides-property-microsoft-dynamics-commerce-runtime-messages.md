---
title: GetTaxOverridesResponse.TaxOverrides Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: TaxOverrides Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetTaxOverridesResponse.TaxOverrides
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.gettaxoverridesresponse.taxoverrides(v=AX.60)
ms:contentKeyID: 62207657
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetTaxOverridesResponse.TaxOverrides
dev_langs:
- CSharp
- C++
- VB
---

# TaxOverrides Property

Gets the channel tax overrides.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TaxOverrides As ReadOnlyCollection(Of TaxOverride)
    Get
    Private Set
'Usage
Dim instance As GetTaxOverridesResponse
Dim value As ReadOnlyCollection(Of TaxOverride)

value = instance.TaxOverrides
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<TaxOverride> TaxOverrides { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<TaxOverride^>^ TaxOverrides {
    ReadOnlyCollection<TaxOverride^>^ get ();
    private: void set (ReadOnlyCollection<TaxOverride^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[TaxOverride](taxoverride-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetTaxOverridesResponse Class](gettaxoverridesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


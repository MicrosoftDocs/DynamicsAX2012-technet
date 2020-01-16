---
title: GetLocalizedStringsResponse.LocalizedStrings Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: LocalizedStrings Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetLocalizedStringsResponse.LocalizedStrings
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getlocalizedstringsresponse.localizedstrings(v=AX.60)
ms:contentKeyID: 62203269
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetLocalizedStringsResponse.LocalizedStrings
dev_langs:
- CSharp
- C++
- VB
---

# LocalizedStrings Property

Gets the localized strings.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LocalizedStrings As ReadOnlyCollection(Of LocalizedString)
    Get
    Private Set
'Usage
Dim instance As GetLocalizedStringsResponse
Dim value As ReadOnlyCollection(Of LocalizedString)

value = instance.LocalizedStrings
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<LocalizedString> LocalizedStrings { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<LocalizedString^>^ LocalizedStrings {
    ReadOnlyCollection<LocalizedString^>^ get ();
    private: void set (ReadOnlyCollection<LocalizedString^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[LocalizedString](localizedstring-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetLocalizedStringsResponse Class](getlocalizedstringsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


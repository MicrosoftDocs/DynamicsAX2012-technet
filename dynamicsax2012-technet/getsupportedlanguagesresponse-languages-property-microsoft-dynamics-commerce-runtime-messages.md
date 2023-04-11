---
title: GetSupportedLanguagesResponse.Languages Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Languages Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetSupportedLanguagesResponse.Languages
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getsupportedlanguagesresponse.languages(v=AX.60)
ms:contentKeyID: 62211572
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetSupportedLanguagesResponse.Languages
dev_langs:
- CSharp
- C++
- VB
---

# Languages Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of language.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Languages As ReadOnlyCollection(Of SupportedLanguage)
    Get
    Private Set
'Usage
Dim instance As GetSupportedLanguagesResponse
Dim value As ReadOnlyCollection(Of SupportedLanguage)

value = instance.Languages
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<SupportedLanguage> Languages { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<SupportedLanguage^>^ Languages {
    ReadOnlyCollection<SupportedLanguage^>^ get ();
    private: void set (ReadOnlyCollection<SupportedLanguage^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[SupportedLanguage](supportedlanguage-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetSupportedLanguagesResponse Class](getsupportedlanguagesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


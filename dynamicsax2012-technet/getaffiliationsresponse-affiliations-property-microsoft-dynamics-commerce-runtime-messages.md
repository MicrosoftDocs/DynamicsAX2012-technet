---
title: GetAffiliationsResponse.Affiliations Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Affiliations Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetAffiliationsResponse.Affiliations
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getaffiliationsresponse.affiliations(v=AX.60)
ms:contentKeyID: 62212460
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetAffiliationsResponse.Affiliations
dev_langs:
- CSharp
- C++
- VB
---

# Affiliations Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets affiliations.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Affiliations As ReadOnlyCollection(Of Affiliation)
    Get
    Private Set
'Usage
Dim instance As GetAffiliationsResponse
Dim value As ReadOnlyCollection(Of Affiliation)

value = instance.Affiliations
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<Affiliation> Affiliations { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<Affiliation^>^ Affiliations {
    ReadOnlyCollection<Affiliation^>^ get ();
    private: void set (ReadOnlyCollection<Affiliation^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Affiliation](affiliation-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetAffiliationsResponse Class](getaffiliationsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


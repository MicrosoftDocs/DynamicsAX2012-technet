---
title: GetButtonGridsByIdsResponse.ButtonGrids Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ButtonGrids Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetButtonGridsByIdsResponse.ButtonGrids
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getbuttongridsbyidsresponse.buttongrids(v=AX.60)
ms:contentKeyID: 62210034
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetButtonGridsByIdsResponse.ButtonGrids
dev_langs:
- CSharp
- C++
- VB
---

# ButtonGrids Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the buttongrids.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ButtonGrids As ReadOnlyCollection(Of ButtonGrid)
    Get
    Private Set
'Usage
Dim instance As GetButtonGridsByIdsResponse
Dim value As ReadOnlyCollection(Of ButtonGrid)

value = instance.ButtonGrids
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<ButtonGrid> ButtonGrids { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<ButtonGrid^>^ ButtonGrids {
    ReadOnlyCollection<ButtonGrid^>^ get ();
    private: void set (ReadOnlyCollection<ButtonGrid^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ButtonGrid](buttongrid-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetButtonGridsByIdsResponse Class](getbuttongridsbyidsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


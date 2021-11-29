---
title: GetParentKitDataResponse.KitComponents Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: KitComponents Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetParentKitDataResponse.KitComponents
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getparentkitdataresponse.kitcomponents(v=AX.60)
ms:contentKeyID: 65321612
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetParentKitDataResponse.KitComponents
dev_langs:
- CSharp
- C++
- VB
---

# KitComponents Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the kit component collection.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property KitComponents As ReadOnlyCollection(Of KitComponent)
    Get
    Private Set
'Usage
Dim instance As GetParentKitDataResponse
Dim value As ReadOnlyCollection(Of KitComponent)

value = instance.KitComponents
```

``` csharp
public ReadOnlyCollection<KitComponent> KitComponents { get; private set; }
```

``` c++
public:
property ReadOnlyCollection<KitComponent^>^ KitComponents {
    ReadOnlyCollection<KitComponent^>^ get ();
    private: void set (ReadOnlyCollection<KitComponent^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[KitComponent](kitcomponent-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetParentKitDataResponse Class](getparentkitdataresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


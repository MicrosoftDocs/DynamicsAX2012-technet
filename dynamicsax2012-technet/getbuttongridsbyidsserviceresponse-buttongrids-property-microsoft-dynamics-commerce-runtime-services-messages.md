---
title: GetButtonGridsByIdsServiceResponse.ButtonGrids Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ButtonGrids Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetButtonGridsByIdsServiceResponse.ButtonGrids
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getbuttongridsbyidsserviceresponse.buttongrids(v=AX.60)
ms:contentKeyID: 62202908
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetButtonGridsByIdsServiceResponse.ButtonGrids
dev_langs:
- CSharp
- C++
- VB
---

# ButtonGrids Property

Gets the buttongrids.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ButtonGrids As ReadOnlyCollection(Of ButtonGrid)
    Get
    Private Set
'Usage
Dim instance As GetButtonGridsByIdsServiceResponse
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

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[ButtonGrid](buttongrid-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetButtonGridsByIdsServiceResponse Class](getbuttongridsbyidsserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


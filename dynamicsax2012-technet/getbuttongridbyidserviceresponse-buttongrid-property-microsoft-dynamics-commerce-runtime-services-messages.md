---
title: GetButtonGridByIdServiceResponse.ButtonGrid Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ButtonGrid Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetButtonGridByIdServiceResponse.ButtonGrid
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getbuttongridbyidserviceresponse.buttongrid(v=AX.60)
ms:contentKeyID: 62210168
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetButtonGridByIdServiceResponse.ButtonGrid
dev_langs:
- CSharp
- C++
- VB
---

# ButtonGrid Property

Gets the buttongrids.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ButtonGrid As ButtonGrid
    Get
    Private Set
'Usage
Dim instance As GetButtonGridByIdServiceResponse
Dim value As ButtonGrid

value = instance.ButtonGrid
```

``` csharp
[DataMemberAttribute]
public ButtonGrid ButtonGrid { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ButtonGrid^ ButtonGrid {
    ButtonGrid^ get ();
    private: void set (ButtonGrid^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGrid](buttongrid-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ButtonGrid](buttongrid-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetButtonGridByIdServiceResponse Class](getbuttongridbyidserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


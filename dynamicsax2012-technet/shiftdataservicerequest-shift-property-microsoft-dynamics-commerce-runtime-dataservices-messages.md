---
title: ShiftDataServiceRequest.Shift Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: Shift Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ShiftDataServiceRequest.Shift
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.shiftdataservicerequest.shift(v=AX.60)
ms:contentKeyID: 65322982
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ShiftDataServiceRequest.Shift
dev_langs:
- CSharp
- C++
- VB
---

# Shift Property

Gets the shift.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Shift As Shift
    Get
    Private Set
'Usage
Dim instance As ShiftDataServiceRequest
Dim value As Shift

value = instance.Shift
```

``` csharp
[DataMemberAttribute]
public Shift Shift { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Shift^ Shift {
    Shift^ get ();
    private: void set (Shift^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [Shift](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ShiftDataServiceRequest Class](shiftdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


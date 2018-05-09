---
title: GetManagerActivityHistoryServiceRequest.EmployeeActivityTypes Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: EmployeeActivityTypes Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetManagerActivityHistoryServiceRequest.EmployeeActivityTypes
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getmanageractivityhistoryservicerequest.employeeactivitytypes(v=AX.60)
ms:contentKeyID: 65323072
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetManagerActivityHistoryServiceRequest.EmployeeActivityTypes
dev_langs:
- CSharp
- C++
- VB
---

# EmployeeActivityTypes Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property EmployeeActivityTypes As EmployeeActivityType()
    Get
    Private Set
'Usage
Dim instance As GetManagerActivityHistoryServiceRequest
Dim value As EmployeeActivityType()

value = instance.EmployeeActivityTypes
```

``` csharp
[DataMemberAttribute]
public EmployeeActivityType[] EmployeeActivityTypes { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property array<EmployeeActivityType>^ EmployeeActivityTypes {
    array<EmployeeActivityType>^ get ();
    private: void set (array<EmployeeActivityType>^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivityType](employeeactivitytype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)\[\]  

## See Also

#### Reference

[GetManagerActivityHistoryServiceRequest Class](getmanageractivityhistoryservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


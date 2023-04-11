---
title: GetEmployeeDataRequestBase Class (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetEmployeeDataRequestBase Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetEmployeeDataRequestBase
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getemployeedatarequestbase(v=AX.60)
ms:contentKeyID: 65319140
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetEmployeeDataRequestBase
dev_langs:
- CSharp
- C++
- VB
---

# GetEmployeeDataRequestBase Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Base class for get employee requests.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public MustInherit Class GetEmployeeDataRequestBase _
    Inherits DataRequest
'Usage
Dim instance As GetEmployeeDataRequestBase
```

``` csharp
[DataContractAttribute]
public abstract class GetEmployeeDataRequestBase : DataRequest
```

``` c++
[DataContractAttribute]
public ref class GetEmployeeDataRequestBase abstract : public DataRequest
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Messages.Request](request-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.DataRequest](datarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetEmployeeDataRequestBase  
        [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetEmployeeDataRequest](getemployeedatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
        [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetEmployeeStoresFromAddressBookDataRequest](getemployeestoresfromaddressbookdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


---
title: ShiftDataServiceRequest Class (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: ShiftDataServiceRequest Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ShiftDataServiceRequest
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.shiftdataservicerequest(v=AX.60)
ms:contentKeyID: 65320393
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ShiftDataServiceRequest
dev_langs:
- CSharp
- C++
- VB
---

# ShiftDataServiceRequest Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The data service request for shifts.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public MustInherit Class ShiftDataServiceRequest _
    Inherits DataRequest
'Usage
Dim instance As ShiftDataServiceRequest
```

``` csharp
[DataContractAttribute]
public abstract class ShiftDataServiceRequest : DataRequest
```

``` c++
[DataContractAttribute]
public ref class ShiftDataServiceRequest abstract : public DataRequest
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Messages.Request](request-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.DataRequest](datarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ShiftDataServiceRequest  
        [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.CreateShiftDataServiceRequest](createshiftdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
        [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.DeleteShiftDataServiceRequest](deleteshiftdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
        [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.UpdateShiftStagingTableDataServiceRequest](updateshiftstagingtabledataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


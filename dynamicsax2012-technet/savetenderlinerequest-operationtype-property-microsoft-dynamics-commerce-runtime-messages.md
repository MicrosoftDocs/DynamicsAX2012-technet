---
title: SaveTenderLineRequest.OperationType Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: OperationType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.SaveTenderLineRequest.OperationType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.savetenderlinerequest.operationtype(v=AX.60)
ms:contentKeyID: 65319177
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.SaveTenderLineRequest.OperationType
dev_langs:
- CSharp
- C++
- VB
---

# OperationType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property OperationType As TenderLineOperationType
    Get
    Set
'Usage
Dim instance As SaveTenderLineRequest
Dim value As TenderLineOperationType

value = instance.OperationType

instance.OperationType = value
```

``` csharp
[DataMemberAttribute]
public TenderLineOperationType OperationType { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property TenderLineOperationType OperationType {
    TenderLineOperationType get ();
    void set (TenderLineOperationType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.TenderLineOperationType](tenderlineoperationtype-enumeration-microsoft-dynamics-commerce-runtime.md)  

## See Also

#### Reference

[SaveTenderLineRequest Class](savetenderlinerequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


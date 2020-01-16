---
title: DeleteStockCountTransactionServiceRequest.InventColorId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: InventColorId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.DeleteStockCountTransactionServiceRequest.InventColorId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.deletestockcounttransactionservicerequest.inventcolorid(v=AX.60)
ms:contentKeyID: 62214138
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.DeleteStockCountTransactionServiceRequest.InventColorId
dev_langs:
- CSharp
- C++
- VB
---

# InventColorId Property

Gets or sets the invent color identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property InventColorId As String
    Get
    Set
'Usage
Dim instance As DeleteStockCountTransactionServiceRequest
Dim value As String

value = instance.InventColorId

instance.InventColorId = value
```

``` csharp
[DataMemberAttribute]
public string InventColorId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ InventColorId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[DeleteStockCountTransactionServiceRequest Class](deletestockcounttransactionservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


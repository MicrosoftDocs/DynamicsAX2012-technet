---
title: DeleteStockCountTransactionServiceRequest.ConfigId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ConfigId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.DeleteStockCountTransactionServiceRequest.ConfigId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.deletestockcounttransactionservicerequest.configid(v=AX.60)
ms:contentKeyID: 62205760
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.DeleteStockCountTransactionServiceRequest.ConfigId
dev_langs:
- CSharp
- C++
- VB
---

# ConfigId Property

Gets or sets the configuration identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ConfigId As String
    Get
    Set
'Usage
Dim instance As DeleteStockCountTransactionServiceRequest
Dim value As String

value = instance.ConfigId

instance.ConfigId = value
```

``` csharp
[DataMemberAttribute]
public string ConfigId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ConfigId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[DeleteStockCountTransactionServiceRequest Class](deletestockcounttransactionservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


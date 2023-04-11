---
title: GetProductDataServiceRequest.ItemIds Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ItemIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetProductDataServiceRequest.ItemIds
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getproductdataservicerequest.itemids(v=AX.60)
ms:contentKeyID: 65321209
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetProductDataServiceRequest.ItemIds
dev_langs:
- CSharp
- C++
- VB
---

# ItemIds Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ItemIds As IEnumerable(Of String)
    Get
    Private Set
'Usage
Dim instance As GetProductDataServiceRequest
Dim value As IEnumerable(Of String)

value = instance.ItemIds
```

``` csharp
[DataMemberAttribute]
public IEnumerable<string> ItemIds { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<String^>^ ItemIds {
    IEnumerable<String^>^ get ();
    private: void set (IEnumerable<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

## See Also

#### Reference

[GetProductDataServiceRequest Class](getproductdataservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)


---
title: GetReceiptMaskDataRequest.FunctionalityProfileId Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: FunctionalityProfileId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetReceiptMaskDataRequest.FunctionalityProfileId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getreceiptmaskdatarequest.functionalityprofileid(v=AX.60)
ms:contentKeyID: 65321737
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetReceiptMaskDataRequest.FunctionalityProfileId
dev_langs:
- CSharp
- C++
- VB
---

# FunctionalityProfileId Property

Gets the functionality profile id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property FunctionalityProfileId As String
    Get
    Private Set
'Usage
Dim instance As GetReceiptMaskDataRequest
Dim value As String

value = instance.FunctionalityProfileId
```

``` csharp
[DataMemberAttribute]
public string FunctionalityProfileId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ FunctionalityProfileId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetReceiptMaskDataRequest Class](getreceiptmaskdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


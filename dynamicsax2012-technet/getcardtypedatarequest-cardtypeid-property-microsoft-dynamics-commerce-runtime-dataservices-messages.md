---
title: GetCardTypeDataRequest.CardTypeId Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: CardTypeId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetCardTypeDataRequest.CardTypeId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getcardtypedatarequest.cardtypeid(v=AX.60)
ms:contentKeyID: 65321000
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetCardTypeDataRequest.CardTypeId
dev_langs:
- CSharp
- C++
- VB
---

# CardTypeId Property

Gets card type ID.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CardTypeId As String
    Get
    Private Set
'Usage
Dim instance As GetCardTypeDataRequest
Dim value As String

value = instance.CardTypeId
```

``` csharp
[DataMemberAttribute]
public string CardTypeId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ CardTypeId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetCardTypeDataRequest Class](getcardtypedatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)


---
title: AddOrRemoveDiscountCodesRequest.DiscountCodes Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: DiscountCodes Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.AddOrRemoveDiscountCodesRequest.DiscountCodes
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.addorremovediscountcodesrequest.discountcodes(v=AX.60)
ms:contentKeyID: 65320838
author: tfehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.AddOrRemoveDiscountCodesRequest.DiscountCodes
dev_langs:
- CSharp
- C++
- VB
---

# DiscountCodes Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DiscountCodes As ReadOnlyCollection(Of String)
    Get
    Private Set
'Usage
Dim instance As AddOrRemoveDiscountCodesRequest
Dim value As ReadOnlyCollection(Of String)

value = instance.DiscountCodes
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<string> DiscountCodes { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<String^>^ DiscountCodes {
    ReadOnlyCollection<String^>^ get ();
    private: void set (ReadOnlyCollection<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

## See Also

#### Reference

[AddOrRemoveDiscountCodesRequest Class](addorremovediscountcodesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


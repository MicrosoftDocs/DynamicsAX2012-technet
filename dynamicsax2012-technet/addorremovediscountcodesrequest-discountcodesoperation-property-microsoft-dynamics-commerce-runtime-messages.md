---
title: AddOrRemoveDiscountCodesRequest.DiscountCodesOperation Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: DiscountCodesOperation Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.AddOrRemoveDiscountCodesRequest.DiscountCodesOperation
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.addorremovediscountcodesrequest.discountcodesoperation(v=AX.60)
ms:contentKeyID: 65316633
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.AddOrRemoveDiscountCodesRequest.DiscountCodesOperation
dev_langs:
- CSharp
- C++
- VB
---

# DiscountCodesOperation Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DiscountCodesOperation As DiscountCodesOperation
    Get
    Private Set
'Usage
Dim instance As AddOrRemoveDiscountCodesRequest
Dim value As DiscountCodesOperation

value = instance.DiscountCodesOperation
```

``` csharp
[DataMemberAttribute]
public DiscountCodesOperation DiscountCodesOperation { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property DiscountCodesOperation DiscountCodesOperation {
    DiscountCodesOperation get ();
    private: void set (DiscountCodesOperation value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountCodesOperation](discountcodesoperation-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[AddOrRemoveDiscountCodesRequest Class](addorremovediscountcodesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


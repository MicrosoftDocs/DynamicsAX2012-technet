---
title: AddOrRemoveDiscountCodesRequest Constructor (String, String, IEnumerable(String), DiscountCodesOperation, Boolean) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: AddOrRemoveDiscountCodesRequest Constructor (String, String, IEnumerable(String), DiscountCodesOperation, Boolean)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.AddOrRemoveDiscountCodesRequest.#ctor(System.String,System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountCodesOperation,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.addorremovediscountcodesrequest.addorremovediscountcodesrequest(v=AX.60)
ms:contentKeyID: 65320167
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# AddOrRemoveDiscountCodesRequest Constructor (String, String, IEnumerable(String), DiscountCodesOperation, Boolean)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    cartId As String, _
    customerAccountNumber As String, _
    discountCodes As IEnumerable(Of String), _
    operation As DiscountCodesOperation, _
    filterByCustomer As Boolean _
)
'Usage
Dim cartId As String
Dim customerAccountNumber As String
Dim discountCodes As IEnumerable(Of String)
Dim operation As DiscountCodesOperation
Dim filterByCustomer As Boolean

Dim instance As New AddOrRemoveDiscountCodesRequest(cartId, _
    customerAccountNumber, discountCodes, _
    operation, filterByCustomer)
```

``` csharp
public AddOrRemoveDiscountCodesRequest(
    string cartId,
    string customerAccountNumber,
    IEnumerable<string> discountCodes,
    DiscountCodesOperation operation,
    bool filterByCustomer
)
```

``` c++
public:
AddOrRemoveDiscountCodesRequest(
    String^ cartId, 
    String^ customerAccountNumber, 
    IEnumerable<String^>^ discountCodes, 
    DiscountCodesOperation operation, 
    bool filterByCustomer
)
```

#### Parameters

  - cartId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - customerAccountNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - discountCodes  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - operation  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountCodesOperation](discountcodesoperation-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - filterByCustomer  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[AddOrRemoveDiscountCodesRequest Class](addorremovediscountcodesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[AddOrRemoveDiscountCodesRequest Overload](addorremovediscountcodesrequest-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


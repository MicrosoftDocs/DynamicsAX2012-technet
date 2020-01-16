---
title: SubmitSalesTransactionRequest.ReceiptEmail Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ReceiptEmail Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.SubmitSalesTransactionRequest.ReceiptEmail
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.submitsalestransactionrequest.receiptemail(v=AX.60)
ms:contentKeyID: 62208367
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.SubmitSalesTransactionRequest.ReceiptEmail
dev_langs:
- CSharp
- C++
- VB
---

# ReceiptEmail Property

Gets or sets the email address the receipt is to be sent to.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<RegularExpressionAttribute("^(?(")("[^"]+?"@)|(([0-9a-zA-Z]((\.(?!\.))|[-!#\$%&'\*\+/=\?\^`\{\}\|~\w])*)(?<=[0-9a-zA-Z])@))(?(\[)(\[(\d{1,3}\.){3}\d{1,3}\])|(([0-9a-zA-Z][-\w]*[0-9a-zA-Z]*\.)+[a-z0-9A-Z]{2,17}))$", ErrorResourceId := "Microsoft_Dynamics_Commerce_Runtime_InvalidAddress")> _
Public Property ReceiptEmail As String
    Get
    Set
'Usage
Dim instance As SubmitSalesTransactionRequest
Dim value As String

value = instance.ReceiptEmail

instance.ReceiptEmail = value
```

``` csharp
[DataMemberAttribute]
[RegularExpressionAttribute("^(?(")("[^"]+?"@)|(([0-9a-zA-Z]((\.(?!\.))|[-!#\$%&'\*\+/=\?\^`\{\}\|~\w])*)(?<=[0-9a-zA-Z])@))(?(\[)(\[(\d{1,3}\.){3}\d{1,3}\])|(([0-9a-zA-Z][-\w]*[0-9a-zA-Z]*\.)+[a-z0-9A-Z]{2,17}))$", ErrorResourceId = "Microsoft_Dynamics_Commerce_Runtime_InvalidAddress")]
public string ReceiptEmail { get; set; }
```

``` c++
[DataMemberAttribute]
[RegularExpressionAttribute(L"^(?(")("[^"]+?"@)|(([0-9a-zA-Z]((\.(?!\.))|[-!#\$%&'\*\+/=\?\^`\{\}\|~\w])*)(?<=[0-9a-zA-Z])@))(?(\[)(\[(\d{1,3}\.){3}\d{1,3}\])|(([0-9a-zA-Z][-\w]*[0-9a-zA-Z]*\.)+[a-z0-9A-Z]{2,17}))$", ErrorResourceId = L"Microsoft_Dynamics_Commerce_Runtime_InvalidAddress")]
public:
property String^ ReceiptEmail {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## Remarks

The validation regular expression string is taken from [How to: Verify that Strings Are in Valid Email Format](https://msdn.microsoft.com/library/01escwtf.aspx).

## See Also

#### Reference

[SubmitSalesTransactionRequest Class](submitsalestransactionrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)


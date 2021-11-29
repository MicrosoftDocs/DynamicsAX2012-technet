---
title: SalesTransaction.ReceiptEmail Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReceiptEmail Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.ReceiptEmail
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.receiptemail(v=AX.60)
ms:contentKeyID: 49841370
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.ReceiptEmail
dev_langs:
- CSharp
- C++
- VB
---

# ReceiptEmail Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the receipt email.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("RECEIPTEMAIL")> _
<RegularExpressionAttribute("^(?(")("[^"]+?"@)|(([0-9a-zA-Z]((\.(?!\.))|[-!#\$%&'\*\+/=\?\^`\{\}\|~\w])*)(?<=[0-9a-zA-Z])@))(?(\[)(\[(\d{1,3}\.){3}\d{1,3}\])|(([0-9a-zA-Z][-\w]*[0-9a-zA-Z]*\.)+[a-z0-9A-Z]{2,17}))$", ErrorResourceId := "Microsoft_Dynamics_Commerce_Runtime_InvalidAddress")> _
Public Property ReceiptEmail As String
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As String

value = instance.ReceiptEmail

instance.ReceiptEmail = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("RECEIPTEMAIL")]
[RegularExpressionAttribute("^(?(")("[^"]+?"@)|(([0-9a-zA-Z]((\.(?!\.))|[-!#\$%&'\*\+/=\?\^`\{\}\|~\w])*)(?<=[0-9a-zA-Z])@))(?(\[)(\[(\d{1,3}\.){3}\d{1,3}\])|(([0-9a-zA-Z][-\w]*[0-9a-zA-Z]*\.)+[a-z0-9A-Z]{2,17}))$", ErrorResourceId = "Microsoft_Dynamics_Commerce_Runtime_InvalidAddress")]
public string ReceiptEmail { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"RECEIPTEMAIL")]
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

The validation regular expression string is taken from \[\!Malformed\!\]MSDN.

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)


---
title: TransactionServiceClient.GetAttributeValue Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: GetAttributeValue Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetAttributeValue(System.Xml.Linq.XElement,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.getattributevalue(v=AX.60)
ms:contentKeyID: 62208994
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetAttributeValue
dev_langs:
- CSharp
- C++
- VB
---

# GetAttributeValue Method

Get attribute value for the given Xml string and attribute name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetAttributeValue ( _
    xmlElement As XElement, _
    attributeName As String _
) As String
'Usage
Dim xmlElement As XElement
Dim attributeName As String
Dim returnValue As String

returnValue = TransactionServiceClient.GetAttributeValue(xmlElement, _
    attributeName)
```

``` csharp
public static string GetAttributeValue(
    XElement xmlElement,
    string attributeName
)
```

``` c++
public:
static String^ GetAttributeValue(
    XElement^ xmlElement, 
    String^ attributeName
)
```

#### Parameters

  - xmlElement  
    Type: [System.Xml.Linq.XElement](https://technet.microsoft.com/en-us/library/bb340098\(v=ax.60\))  

<!-- end list -->

  - attributeName  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns the Attribute value.  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)


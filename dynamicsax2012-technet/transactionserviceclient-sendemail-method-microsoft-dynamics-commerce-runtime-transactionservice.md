---
title: TransactionServiceClient.SendEmail Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: SendEmail Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.SendEmail(System.String,System.String,System.String,System.Collections.Generic.ICollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.NameValuePair},System.Object)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.sendemail(v=AX.60)
ms:contentKeyID: 49821804
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.SendEmail
dev_langs:
- CSharp
- C++
- VB
---

# SendEmail Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Sends an email to a customer using the provided emailId in AX.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Sub SendEmail ( _
    emailAddress As String, _
    language As String, _
    emailId As String, _
    mappings As ICollection(Of NameValuePair), _
    xmlData As Object _
)
'Usage
Dim instance As TransactionServiceClient
Dim emailAddress As String
Dim language As String
Dim emailId As String
Dim mappings As ICollection(Of NameValuePair)
Dim xmlData As Object

instance.SendEmail(emailAddress, language, _
    emailId, mappings, xmlData)
```

``` csharp
public void SendEmail(
    string emailAddress,
    string language,
    string emailId,
    ICollection<NameValuePair> mappings,
    Object xmlData
)
```

``` c++
public:
void SendEmail(
    String^ emailAddress, 
    String^ language, 
    String^ emailId, 
    ICollection<NameValuePair^>^ mappings, 
    Object^ xmlData
)
```

#### Parameters

  - emailAddress  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - language  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - emailId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - mappings  
    Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[NameValuePair](namevaluepair-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - xmlData  
    Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)


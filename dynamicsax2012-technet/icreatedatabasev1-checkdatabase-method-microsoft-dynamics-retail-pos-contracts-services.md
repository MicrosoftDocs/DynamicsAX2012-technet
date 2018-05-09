---
title: ICreateDatabaseV1.CheckDatabase Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: CheckDatabase Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICreateDatabaseV1.CheckDatabase(System.String,System.String,System.Boolean,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.icreatedatabasev1.checkdatabase(v=AX.60)
ms:contentKeyID: 47344343
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICreateDatabaseV1.CheckDatabase
dev_langs:
- CSharp
- C++
- VB
---

# CheckDatabase Method

Checks the specified database.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub CheckDatabase ( _
    connectionString As String, _
    databasePhysicalFilePath As String, _
    includeDemoData As Boolean, _
    userGroupName As String _
)
'Usage
Dim instance As ICreateDatabaseV1
Dim connectionString As String
Dim databasePhysicalFilePath As String
Dim includeDemoData As Boolean
Dim userGroupName As String

instance.CheckDatabase(connectionString, _
    databasePhysicalFilePath, includeDemoData, _
    userGroupName)
```

``` csharp
void CheckDatabase(
    string connectionString,
    string databasePhysicalFilePath,
    bool includeDemoData,
    string userGroupName
)
```

``` c++
void CheckDatabase(
    String^ connectionString, 
    String^ databasePhysicalFilePath, 
    bool includeDemoData, 
    String^ userGroupName
)
```

#### Parameters

  - connectionString  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - databasePhysicalFilePath  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - includeDemoData  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - userGroupName  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ICreateDatabaseV1 Interface](icreatedatabasev1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)


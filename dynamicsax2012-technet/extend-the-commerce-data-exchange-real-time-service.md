---
title: 'Extend the Commerce Data Exchange: Real-time Service'
TOCTitle: 'Extend the Commerce Data Exchange: Real-time Service'
ms:assetid: 79f7d449-f804-4ded-b7f2-92d86b6713d9
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn126098(v=AX.60)
ms:contentKeyID: 52075233
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Extend the Commerce Data Exchange: Real-time Service 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

You can extend Commerce Data Exchange: Real-time Service by adding extension methods to the [RetailTransactionServiceEx](https://technet.microsoft.com/en-us/library/hh813763\(v=ax.60\)) class.

Real-time Service enables retail clients to interact with Microsoft Dynamics AX retail functionality in real time. For more information, see [Commerce Data Exchange: Real-time Service](commerce-data-exchange-real-time-service.md).

## Extending the RetailTransactionServiceEx Class

To extend Real-time Service, you create a new method in the [RetailTransactionServiceEx](https://technet.microsoft.com/en-us/library/hh813763\(v=ax.60\)) class. This method must meet the following criteria:

  - The method must be a public static method.

  - The return value must be a container of length two or more. The first two elements must be a Boolean value that indicates whether the method call was successful and a String value that you can use for a comment or error message. The other items in the container can be of any type, including nested containers.

  - The method parameters must be one of the following Microsoft Dynamics AX primitive types:
    
      - Boolean
    
      - date
    
      - int
    
      - int64
    
      - str
    
      - guid
    
      - Real

### To add a method

1.  In the AOT, right-click **Classes** \> **RetailTransactionServiceEx**, point to **New**, and then click **Method**.

2.  Add your custom business logic.

## Example

The following example shows a method that takes a customer account number and returns a greeting message using the customer’s name. For example, if customer account number 1001 was associated with a customer named Sandy, the method would return “Hello Sandy\!”.

    public static container Hello(AccountNum accountNumber)
    {
        CustTable custTable;
        DirPartyTable dirPartyTable;
        container result = [false, ''];
        
        if (accountNumber)
        {
            select firstOnly Name from dirPartyTable
            exists join custTable
            where custTable.accountNum == accountNumber 
                  && dirPartyTable.RecId == CustTable.Party;
            
            if (dirPartyTable)
            {
                result = [true, 'Success!', strFmt("Hello %1 !", dirPartyTable.Name)];
            }
            else
            {
                result = [false, 'Customer not found'];
            }
        }
        else
        {
            result = [false, 'accountNumber is null.'];
        }
        
        return result;
    }

The following example demonstrates calling the new method from the commerce runtime.

    public void HelloCustomer(string accountNumber)
            {
                try
                {
                    var response = this. PosApplication.Instance.TransactionServices.InvokeExtension("Hello", "2014");
                    if (response.Count == 1)
                    {
                        Console.WriteLine(response[0] as string);
                    }
                }
                catch (CommunicationException ex)
                {
                    Console.WriteLine("Request failed: {0}", ex.Message);
                }
            }

Note that the response comments have been abstracted. If the request fails, the service client will throw a communication exception. Only the additional response data is returned.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


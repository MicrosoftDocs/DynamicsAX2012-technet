---
title: (RUS) Set up address information for a party, customer, vendor, worker, or  legal entity
TOCTitle: (RUS) Set up address information for a party, customer, vendor, worker, or  legal entity
ms:assetid: 8be84c8a-8758-4d12-9ed7-9e0e1b92e637
ms:mtpsurl: https://technet.microsoft.com/library/JJ735280(v=AX.60)
ms:contentKeyID: 49693281
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- vendor
- customer
- Set up
- legal entity
- (RUS)
- Russia
- address information
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up address information for a party, customer, vendor, worker, or legal entity 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can set up address information for customers, vendors, workers, and legal entities. The global address book (GAB) in Microsoft Dynamics AX contains consolidated address information for customers, vendors, contacts, business relations, and legal entities. For more information see, [Global address book overview](global-address-book-overview.md).

In the Russian Federation, regions, states, counties, cities, districts, and streets have unique numbers. The Russian address formats include address components such as the **County**, **City**, and **Street** fields. You can also enter values in the **Country/region**, **State**, **District**, **Group of houses**, and **Group of flats** fields. If you change the value in the **ZIP/postal code** field, the other address fields are updated.

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**. Double-click a customer line to open the **Customers** form. In the **Customers** form, on the **Addresses** FastTab, click **More options**, and then click **Advanced** to open the **Manage addresses** form.
    
    –or–
    
    Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**. Double-click a vendor line to open the **Vendors** form. In the **Vendors** form, on the **Addresses** FastTab, click **More options**, and then click **Advanced** to open the **Manage addresses** form.
    
    –or–
    
    Click **Organization administration** \> **Setup** \> **Organization** \> **Legal entities**. Double-click a legal entity line to open the **Legal entities** form. In the **Legal entities** form, on the **Addresses** FastTab, click **More options**, and then click **Advanced** to open the **Manage addresses** form.
    
    –or–
    
    Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**. Click **Registration** \> **Taxes**.
    
    –or–
    
    Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**. Click **Registration** \> **Taxes**.
    
    –or–
    
    Click **Organization administration** \> **Setup** \> **Organization** \> **Legal entities**. Click **Taxes**.

2.  In the **ZIP/postal code** field, select the ZIP Code or postal code. The corresponding state, country/region, and ZIP Code or postal code are displayed.
    

    > [!NOTE]
    > <P>The <STRONG>County</STRONG>, <STRONG>City</STRONG>, and <STRONG>District</STRONG> fields display the county, city, and district code when the ZIP Code or postal code is specified.</P>



3.  In the **Street code** field, select the street code. The corresponding name and ZIP Code or postal code are displayed.

4.  In the **Building complement** field, enter the building name for the customer, vendor, worker, or legal entity.

5.  In the **Street** field, enter the concatenated details of the street name, number of buildings, building complements, and apartments for the customer, vendor, worker, or legal entity.

6.  In the **Group of houses** field, select the group of houses code for the customer, vendor, worker, or legal entity. The corresponding number of buildings, buildings, and ZIP Code or postal codes are displayed.

7.  In the **Group of flats** field, select the group of flats code for the customer, vendor, worker, or legal entity. The corresponding number of entrances and ZIP Code or postal code are displayed.

8.  On the **Tax registration** tab, click **Add**. Enter information about tax registration, and then specify the effective date and expiration date for the tax registration numbers.

## See also

[Customers (form)](https://technet.microsoft.com/library/aa590606\(v=ax.60\))

[Vendors (form)](https://technet.microsoft.com/library/aa592162\(v=ax.60\))

[Legal entities (form)](https://technet.microsoft.com/library/hh242860\(v=ax.60\))

  



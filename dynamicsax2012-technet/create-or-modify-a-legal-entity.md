---
title: Create or modify a legal entity
TOCTitle: Create or modify a legal entity
ms:assetid: 35fd4342-77d6-45ea-bc2e-ae416945c856
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242184(v=AX.60)
ms:contentKeyID: 36056575
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Create or modify a legal entity [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A legal entity is an organization that is identified through registration with a legal authority. Legal entities can enter into contracts and are required to prepare statements that report on their performance.

Use the information in this topic to create a new legal entity or modify an existing legal entity. If you are using Microsoft Dynamics AX 2012 R3 or AX 2012 R2, legal entities must be configured separately for each partition.

Organizations that are relevant to other application areas can also be set up in Human resources and General ledger.


> [!NOTE]
> <P>For information about fields that are not described in this topic, press <STRONG>F1</STRONG> in the <STRONG>Legal entities</STRONG> form.</P>



1.  Click **Organization administration** \> **Setup** \> **Organization** \> **Legal entities**.

2.  To create a new legal entity, click **New**. The **New legal entity** form is displayed, where you can enter the required information for a legal entity record. Enter information in the **Name**, **Company**, **Country/region** fields and click **OK**.
    

    > [!IMPORTANT]
    > <P>A company is a unique identifier for the data that is associated with the legal entity. A company can be associated with only one legal entity, and a legal entity can be associated with only one company.</P>

    
    Depending on your version of the program, use one of the following methods to modify the name of a legal entity:
    
      - In Microsoft Dynamics AX 2012 R3 or AX 2012 R2, select the legal entity, and then in the **Name** field, enter the new name.
    
      - Otherwise, select the legal entity in the list, click **Change name**, and then enter the new name.
        
        You cannot change the company that is associated with an existing legal entity.

3.  On the **General** FastTab, provide the following general information about the legal entity:
    
      - Enter a search name, if a search name is required. A search name is an alternate name that can be used to search for this legal entity by using Enterprise Search.
    
      - Select whether this legal entity is being used as a consolidation company.
        
        In a consolidation, you gather transactions from several company accounts into a single company. You can print reports, such as financial statements, from the consolidated company, but you cannot use the company for daily transactions.
        
        For more information about consolidation, see [Consolidate transactions](consolidate-transactions.md).
    
      - Select whether this legal entity is being used as an elimination company.
        
        When a parent company does business with one or more subsidiary companies and uses consolidated financial reporting, any transactions between the companies must be removed, or eliminated, from the financial reports. These transactions are called elimination transactions. The destination company for eliminations is called the elimination company.
        
        For more information about elimination, see [Eliminate transactions](eliminate-transactions.md).

4.  On the **Addresses** FastTab, enter address information, such as the street name and number, postal code, and city. Click **New** to enter a new address record, or click **Edit** to modify an existing address record. For more information about the address fields, press **F1** in the forms that open when you click **New** or **Edit**.
    

    > [!IMPORTANT]
    > <P>The country/region that you select for the primary address of the legal entity controls the country/region-specific features that are available for the legal entity.</P>



5.  On the **Contact information** FastTab, enter information about methods of communication, such as email addresses, URLs, and telephone numbers. To enter a new communication record, click **New**. To modify an existing communication record, click **More options** \> **Advanced**. For more information about the communication fields, press **F1** in the forms that open when you click **New** or **Advanced**.

6.  On the **Tax registration** FastTab, enter the registration numbers that are used to report to tax authorities.

7.  On the **Withholding tax** FastTab, enter 1099 information for the legal entity.
    

    > [!NOTE]
    > <P>(USA) The fields on this tab are available only to legal entities whose primary address is in the United States.</P>



8.  On the **Statutory reporting** FastTab, enter the registration numbers that are used for statutory reporting.

9.  On the **Bank account information** FastTab, enter bank accounts and routing numbers for the legal entity.

10. On the **Foreign trade and logistics** FastTab, enter shipping information for the legal entity. This shipping information includes Intrastat information.

11. On the **Number sequences** FastTab, you can view the number sequences that are associated with the legal entity. To change this information, use the **Number sequences** form. (Click **Organization administration** \> **Common** \> **Number sequences** \> **Number sequences**.)

12. To view or change the logo that is associated with the legal entity, click **Company logo**.

13. To view the legal entity in the organizational hierarchy, click **View in hierarchy**.

14. Information about legal entities is saved when you select a different line in the list or close the form.

## See also

[About organizations and organizational hierarchies](about-organizations-and-organizational-hierarchies.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


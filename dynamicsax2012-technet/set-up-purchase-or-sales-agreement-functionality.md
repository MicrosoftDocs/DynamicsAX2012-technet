---
title: Set up purchase or sales agreement functionality
TOCTitle: Set up purchase or sales agreement functionality
ms:assetid: 32d8f14f-b654-405f-a439-ab394260751a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh802995(v=AX.60)
ms:contentKeyID: 44080967
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- setup
- set up
- purchase agreement
- sales agreement
- sales agreements
- purchase agreements
---

# Set up purchase or sales agreement functionality 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes the following key steps to set up a purchase agreement or a sales agreement:

  - Enable configuration keys.

  - Set up a number sequence.

  - Set up a classification for purchase agreements and sales agreements.

## Enable configuration keys

The following configuration keys must be selected to enable purchase agreements and sales agreements:

  - **Purchase and sales agreement** configuration key (TradeBlanketOrder)

  - Optional: **Project I** configuration key (ProjBasic)

  - Optional: **Public sector** configuration key (PublicSector)

The **Purchase and sales agreement** configuration key must be enabled. Additionally, the **Project I** configuration key must be enabled to make the project fields available in the **Purchase agreements** and **Sales agreements** forms, and to make purchase agreements and sales agreements available in **Project**.

For more information about how to enable configuration keys, see [Configure application functionality](configure-application-functionality.md).

## Set up a number sequence

Number sequences automatically assign identification numbers to purchase agreements in the **Purchase agreement** form or sales agreements in the **Sales agreements** form. Before you create any new purchase agreements or sales agreements, follow these steps to set up a number sequence.

1.  In the **Number sequences** form, create a number sequence:
    
    1.  Click **Organization administration** \> **Common** \> **Number sequences** \> **Number sequences**.
    
    2.  On the **Action Pane**, click **Number sequence** to create a new number sequence.
    
    3.  In the **Number sequence code** field, enter a code for the number sequence.
    
    4.  In the **Name** field, enter a description of how and where the number sequence is used. For example, if the number sequence is used for purchase agreements, you might enter **Purchase agreement**.
    
    5.  On the **Segments** tab, define the format for the number sequence. Use the number sign (\#) for numbers and the ampersand (&) for letters.
    
    6.  On the **General** tab, define the interval and increment for the number sequence.
    
    7.  Select the **Continuous** check box.
        

        > [!NOTE]
        > <P>To enable purchase agreement IDs or sales agreement IDs to be entered manually, select the <STRONG>Manual</STRONG> check box. For more information about the fields in this form, see <A href="https://technet.microsoft.com/en-us/library/aa600321(v=ax.60)">Number sequences (list page)</A>.</P>

    
    8.  On the **References** FastTab, click **Add**, and then select a module and an agreement ID.
        
          - For purchase agreements, select **Purchase** and **Purchase agreement ID**.
        
          - For sales agreements, select **Sales** and **Sales agreement ID**.

2.  For purchase agreements, select and apply the number sequence in the **Procurement and sourcing parameters** form:
    
    1.  Click **Procurement and sourcing** \> **Setup** \> **Procurement and sourcing parameters**.
    
    2.  Click the **Number sequences** column, and then, in the grid, locate the reference for the purchase agreement.
    
    3.  In the **Number sequence code** column, select the number sequence that you defined in the **Number sequences** form.
    
    4.  Close the form.

3.  For sales agreements, select and apply the number sequence in the **Accounts receivable parameters** form:
    
    1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.
    
    2.  Click the **Number sequences** column, and then, in the grid, locate the reference for the sales agreement.
    
    3.  In the **Number sequence code** column, select the number sequence that you defined in the **Number sequences** form.
    
    4.  Close the form.

## Set up a classification for purchase agreements and sales agreements

When you create a new purchase agreement or sales agreement, you must always select the type of purchase agreement or sales agreement. You can also define your own purchase or sales agreement types, which allows you to use names that fit the domain of your organization, such as Blanket order.


> [!IMPORTANT]
> <P>When Microsoft Dynamics AX 2009 is upgraded to Microsoft Dynamics AX 2012, purchase orders and sales orders that have a <STRONG>Blanket order</STRONG> type are automatically converted to purchase agreements and sales agreements, respectively. The default agreement type for purchase agreements is <STRONG>Blanket purchase agreement</STRONG>. The default agreement type for sales agreements is <STRONG>Blanket sales agreement</STRONG>.</P>



Follow these steps to create agreement types.

1.  Click **Procurement and sourcing** \> **Setup** \> **Purchase agreements** \> **Purchase agreement classification**.
    
    –or–
    
    Click **Sales and marketing** \> **Setup** \> **Sales agreements** \> **Sales agreement classifications**.

2.  Enter a name in the **Name** field. If a name is already displayed in the grid, click **New**, and then enter a name.

3.  To define agreement types for a specific locale, click **Translations** to open a form where you can create one name per language.

4.  If the **Public sector** configuration key is selected, additional controls are available for purchase agreements.
    
      - To enter information about subcontractors on purchase agreements that use this classification, select the **Subcontractors** check box.
    
      - To enter information about insurance policies and bonds on purchase agreements that use this classification, select the **Certifications** check box.
    
      - To enter information about milestones and tasks on purchase agreements that use this classification, select the **Activities** check box.
    
      - To require the use of direct invoicing and prevent the use of release orders with purchase agreements that use this classification, select the **Require direct invoicing** check box.


> [!NOTE]
> <P>You cannot delete an agreement type that is currently used for existing purchase agreements or sales agreements.</P>



## See also

[Purchase agreements (form)](https://technet.microsoft.com/en-us/library/hh209550\(v=ax.60\))

[Sales agreements (form)](https://technet.microsoft.com/en-us/library/hh209567\(v=ax.60\))

[Number sequences (list page)](https://technet.microsoft.com/en-us/library/aa600321\(v=ax.60\))

[Agreement classification (form)](https://technet.microsoft.com/en-us/library/hh802986\(v=ax.60\))

[Purchase and sales agreement configuration key (TradeBlanketOrder)](purchase-and-sales-agreement-configuration-key-tradeblanketorder.md)

[Project I configuration key (ProjBasic)](project-i-configuration-key-projbasic.md)

[Public sector configuration key (PublicSector)](public-sector-configuration-key-public-sector.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


---
title: Configure user relations
TOCTitle: Configure user relations
ms:assetid: 5c6ace7f-858d-4d84-9aec-a1d29d480893
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dd309687(v=AX.60)
ms:contentKeyID: 35132651
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Configure user relations 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Users can be internal or external. Internal users include employees, and external users include vendors, prospective vendors, customers, and prospects. After you specify user relations, a user's information, such as the employee ID or customer account ID, is automatically displayed in fields when that user opens a page in Enterprise Portal for Microsoft Dynamics AX.

For external relations, data in the vendor portal is restricted based on vendor account and legal entities identified under **External relations**. For example, if a user has an external relation for vendor account 1003 and legal entity 1234, the user sees data only for vendor account 1003 and any transactions with legal entity 1234 in the vendor portal.


> [!IMPORTANT]
> <P>User relations trim data based on a user's designated role and account, but they do not enforce security in Enterprise Portal. In Enterprise Portal, security is enforced through Microsoft Dynamics AX role-based security and Microsoft SharePoint permissions. For more information, see <A href="checklist-configure-enterprise-portal-security.md">Checklist: Configure Enterprise Portal security</A>.</P>



This topic includes information about the following:

  - Configure a user account to have a user relation

  - Configure a user account to have multiple external user relations

## Configure a user account to have a user relation

1.  Click **System administration** \> **Common** \> **Users** \> **User relations**.

2.  Click **New**.

3.  In the **Person** list, select the person, and then click **OK**.
    
    If you do not see the person's name in this list, the person has not completed the customer/partner on-boarding processes and their details are not available in the global address book.

4.  In the **User ID** list, select the Microsoft Dynamics AX user ID for this relation. If you do not see the user ID that you want to assign, verify that the ID was added to the list of Microsoft Dynamics AX users.

5.  If the user is external to your business or organization, such as a customer or partner, click the **Add** button under **External relations**.
    

    > [!TIP]
    > <P>If the <STRONG>Add</STRONG> button is not active, press F5 to refresh the form.</P>

    
    1.  In the **Relation type** list, select the type of external relation for this user.
    
    2.  In the **Legal entity** list, select the legal entity for this relation.
    
    3.  In the **Name** list, select the user's business or organization.

6.  Click **Close** to save your changes.

## Configure a user account to have multiple external user relations

This section describes three ways to configure a user account to have multiple external user relations. Multiple external relations are necessary if, for example, a user account is listed as a vendor in two companies and the user must access data from both companies in Enterprise Portal. If you do not perform the steps in this procedure and you try to, for example, add more than one external account to the external relations for a vendor, the system displays a warning: *External relation for \<vendor name\> cannot be added. It does not relate to any of the existing external relations for this AX user.*

## Method 1: Add vendor to another legal entity on the User Relations form

1.  Open the **User relations** form in company A. Click **System administration** \> **Common** \> **Users** \> **User relations**.

2.  Click **New**.

3.  In the **Person** list, select the person, and then click **OK**.
    
    If you do not see the person's name in this list, the person has not completed the customer/partner on-boarding processes and their details are not available in the global address book.

4.  Under **External relations**, click the **Add** button to add multiple relations.
    

    > [!TIP]
    > <P>If the <STRONG>Add</STRONG> button is not active, press F5 to refresh the form.</P>

    
    1.  In the **Relation type** list, select the type of external relation for this user.
    
    2.  In the **Legal entity** list, select the legal entity for this relation.
    
    3.  In the **Name** list, select the user's business or organization.

5.  Click **Close** to save your changes.

## Method 2: Merge party IDs

If both vendor records already are located in the global address book, you can merge the party IDs for the vendor records. After you merge the party IDs you must specify user relations, as described in this topic. For more information about merging party IDs, see [Merge party IDs for vendor accounts across multiple legal entities](merge-party-ids-for-vendor-accounts-across-multiple-legal-entities.md).

## Method 3: Configure multiple vendor records to use the same Party ID

If both vendor records already are located in the global address book, you can change the party association for one of the vendor records.

1.  In company A, on the **Vendor** page, select the vendor record and then click the **Change party association** button. Note the vendor’s associated party ID.

2.  Locate the vendor’s associated party ID in company B.

3.  Determine which party ID you want to keep and which ID you want to change.

4.  Use the **Change party association** button to change the associated party ID that you want to change to the ID that you want to keep. To say this another way, change one record so that both vendor records use the same party ID.

5.  Specify user relations as described earlier in this topic.

## See also

[Checklists for deploying Enterprise Portal sites](checklists-for-deploying-enterprise-portal-sites.md)

[Enterprise Portal and Role Centers security and protection](enterprise-portal-and-role-centers-security-and-protection.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).


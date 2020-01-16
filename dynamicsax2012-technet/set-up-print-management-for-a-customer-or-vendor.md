---
title: Set up print management for a customer or vendor
TOCTitle: Set up print management for a customer or vendor
ms:assetid: fb5cedee-5b96-475a-a038-d61fcf01f42c
ms:mtpsurl: https://technet.microsoft.com/library/Dd362137(v=AX.60)
ms:contentKeyID: 36060079
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- print
- vendor
- vendors
- customer
- customers
- printing
- printer
- printers
audience: Application User
ms.search.region: Global
---

# Set up print management for a customer or vendor 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to set up print management for a specific customer or vendor. This procedure assumes that print management was previously set up for a module. For more information, see [Set up print management for a module](set-up-print-management-for-a-module.md).

If you will be emailing the documents to a group of email addresses that have the same business purpose or worker title, you must set up the purposes or titles, first. For more information, see [Address purpose (form)](https://technet.microsoft.com/library/hh242741\(v=ax.60\)). You set up purposes in the **Address and contact information purpose** form. Click **Organization administration** \> **Setup** \> **Global address book** \> **Address and contact information purpose**. You assign purposes in the **Customers** or **Vendors** form, on the **Contact information** FastTab, in the **Purpose** field. You assign worker titles in the **Worker** form, in the **Title** field. Click **Human resources** \> **Setup** \> **Workers** \> **Titles**.

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.
    
    –or–
    
    Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.

2.  Select an account.

3.  On the **Action Pane**, click the **General** tab. In the **Set up** group, click **Print management**.

4.  In the left pane, expand the list for a document that is listed under the customer or vendor account that you are working with. Any original or copy records are displayed.
    

    > [!NOTE]
    > <P>An icon with a blue arrow indicates that the original or copy record is inherited from the module level of the hierarchy. This is the print management information that is used for the customer or vendor, unless you override it and make changes at the account level.</P>



5.  Review the original or copy record information. If changes are needed, you can override an inherited record, copy an inherited record, create a new record, or create a new setting.
    
      - To override, right-click an original or copy record and select **Override**. The icon changes to display a red X to indicate that the record is now an override record.
    
      - To copy, right-click an original or copy record and select **Copy**. A copy is displayed in the list. You must give the copy a new name.
    
      - To create a new original or copy record, right-click a document in the list and select **New**. A new record is displayed in the list.
    
      - To create a new conditional setting, right-click an original or copy record and select **New**. A new conditional setting is displayed in the list. You must give the conditional setting a description and select query information.

6.  By default, the document will be sent to the default printer. To change the printer destination, click **Destination** lookup button \> **Printer setup** and select a destination. When you have finished making changes, click **OK** to return to the **Print management setup** form.

7.  If you want to email the documents, complete the following steps:
    
    1.  In the **Print destination settings** form, select **E-mail** as the print destination.
    
    2.  Click the **Edit** button.
        
        This control is not available in versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.
    
    3.  In the **Assign email addresses** form, in the **%1 purpose** field, you can select a business purpose to send the document to a group of email addresses that have the same assigned purpose.
    
    4.  Select the **%1 primary contact** check box to email the report to the primary contact assigned to the customer or vendor.
    
    5.  In the **Worker title** field, you can select a title to send the report to a group of workers who have the same assigned title.
    
    6.  In the **Additional email addresses, separated by ";"** field, you can enter additional email addresses to email the document to.

8.  Select a report format.
    
    The report format must be created by a developer and be added to the Application Object Tree (AOT) before it is available for selection in the **Print management setup** form. Report formats can be specific to a country/region.

9.  Enter the number of identical copies to print.

10. Enter the footer text to include at the bottom of the document. To print footer text in other languages, depending on the language of the document, click the **Footer text** lookup button and set up footer text for the additional languages.

11. Repeat steps 4 through 10 for the remaining documents in the list.

## See also

[Print management setup (form)](https://technet.microsoft.com/library/hh209383\(v=ax.60\))

[Set up print management for a module](set-up-print-management-for-a-module.md)

[Set up print management for a transaction](set-up-print-management-for-a-transaction.md)

  



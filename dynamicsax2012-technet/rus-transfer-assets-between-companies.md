---
title: (RUS) Transfer assets between companies
TOCTitle: (RUS) Transfer assets between companies
ms:assetid: 37f94824-4ba9-4a04-b3dc-b863af83050a
ms:mtpsurl: https://technet.microsoft.com/library/JJ665281(v=AX.60)
ms:contentKeyID: 49387370
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Transfer assets between companies 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



You can create individual transfer transactions to transfer assets to another company. If the companies have separate databases, transfer transactions are created in the company that you are transferring an asset from, and receipt transactions are created in the company that that you are transferring the asset to.

## Adjust the value model settings to transfer an asset

Before you create fixed assets transfers between companies, you must adjust the settings of the value models.

1.  Click **Fixed assets** \> **Setup** \> **Value models**.

2.  On the **Overview** tab, press CTRL+N and create a value model.

3.  On the **Map** tab, in the **Company accounts ID** field, select the company code that the asset will be transferred to.

4.  In the **Value model** field, select the value model number that corresponds to the current account for the company.

## Transfer an asset to another company

1.  Click **Fixed assets** \> **Common** \> **Fixed assets** \> **Fixed assets**.

2.  On the **Overview** tab, select the asset to be transferred.

3.  Click **History** \> **Issue**.

4.  In the **Date** field, enter the date of the transfer.

5.  In the **Company accounts ID** field enter the code for the company receiving the asset, if necessary.

6.  In the **Fixed asset** field, modify the code for the asset, if necessary.
    

    > [!NOTE]
    > <P>After you select the company that is receiving the asset, you can select the inventory number that corresponds to the asset after the transfer. The statuses of the assets are <STRONG>Scheduled</STRONG> and <STRONG>Written off</STRONG>. Assets with a <STRONG>Written off</STRONG> status can be returned after transfer only if you have selected a company in the <STRONG>Company</STRONG> field.</P>



7.  The **Posted** field in the **Issue to another company** form is updated after a transfer transaction in the fixed assets journal is posted. The ledger accounts of the receiving company are updated to acknowledge the transaction.
    
    On the **General** tab, information is displayed about the transfer journal used to transfer the asset, if the journal was created and closed. If the journal was not created, you can enter the document number and date manually.
    
    Information on the **Value models** tab is displayed when posting a transfer transaction in the fixed assets journal. This information cannot be modified. The number of lines displayed on the **Value models** tab must be equal to the number of models that the transaction was posted for.
    
    The value model, balance cost, and book depreciation for the asset that was transferred are displayed, along with the period that the asset was used prior to the transfer.

8.  Click **Fixed assets (Russia)** \> **Journals** \> **FA journal**.

9.  Click **Lines**. Enter the transfer transaction in the lines of the journal. This is similar to creating an acquisition transaction.
    

    > [!NOTE]
    > <P>The date of the transaction in the fixed assets journal cannot be earlier than the date that the transfer was registered in the asset history.</P>



10. Click **Post** \> **Post**. If the transaction included all value models, the status of the asset is **Written off**. Value model information for the receiving company is updated in the **Transfer** form.
    

    > [!NOTE]
    > <P>In the <STRONG>Receipt from another company</STRONG> form, the fields on the <STRONG>Overview</STRONG> and <STRONG>Value models</STRONG> tabs are updated for the asset record. When you transfer an asset to another company, the material asset types in the records for the asset being transferred and accepted is not verified automatically. You must verify that information in the <STRONG>Type</STRONG> field on the <STRONG>General</STRONG> tab of the <STRONG>Fixed assets</STRONG> form.</P>



## Transfer groups of fixed assets

1.  Click **Fixed assets (Russia)** \> **Journals** \> **Transfer journals** \> **Transference to another company**.

2.  On the **Overview** tab, press CTRL+N to create a new line, and then in the **Date** field, enter the date for the asset transfer.

3.  In the **Company accounts ID** field, enter the account ID for the receiving company, if the company shares the same database.
    

    > [!NOTE]
    > <P>The journal number is based on the configured number sequence. However, you can enter it manually.</P>



4.  Click **Lines**.

5.  In the **Lines of FA transfer journal** form, press CTRL+N to create a new line.

6.  In the **Source** field, select the number for the asset that is being transferred.
    

    > [!NOTE]
    > <P>Available assets have an <STRONG>Exploitation</STRONG> status. The name of the asset being transferred is displayed in the <STRONG>Account name</STRONG> field. If the receiving company is specified for the journal, its name is displayed in the <STRONG>Destination company</STRONG> field.</P>



7.  In the **Destination** field, select the asset number of the receiving company that corresponds to the asset that is being transferred.
    

    > [!NOTE]
    > <P>Available assets have a <STRONG>Scheduled</STRONG> or <STRONG>Written off</STRONG> status. The account that the asset is transferred to is displayed in the <STRONG>Account name</STRONG> field based on your entry in the <STRONG>Destination</STRONG> field.</P>



8.  Create the required number of lines and close the form.

9.  Click **Close** in the **Issue to another company** form. The **Posted** check box on the **Overview** tab will be selected, and information about the transfer will be displayed in the history of the FA/IAs specified in the journal lines.

10. Post the transfer transaction in the FA journal.

## See also

[(RUS) Transfer multiple assets using the Fixed asset transfer journal](rus-transfer-multiple-assets-using-the-fixed-asset-transfer-journal.md)

  



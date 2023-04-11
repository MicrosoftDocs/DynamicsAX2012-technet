---
title: (RUS) Set up an electronic exchange format for a client bank
TOCTitle: (RUS) Set up an electronic exchange format for a client bank
ms:assetid: 895b66cb-e2c7-44f4-88a7-e8a442a51521
ms:mtpsurl: https://technet.microsoft.com/library/JJ839677(v=AX.60)
ms:contentKeyID: 50396823
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up an electronic exchange format for a client bank 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Exchange formats of client-bank** form to set up an electronic exchange format, so that you can import or export payments by using a client bank. To create an exchange interface with a client bank, you must set up an exchange format code, list of fields, field order number, and field separator character. You can then assign an exchange format to a bank account.

1.  Click **Cash and bank management** \> **Setup** \> **Electronic formats**.

2.  Press CTRL+N to create a new exchange format. Then, in the **Exchange format code** field, enter a unique code for the exchange format, such as 1C.

3.  In the **Type of exchange format** field, select the type of exchange format from the following options:
    
      - **Separate by sections** – The sections in the imported or exported document are separated by a symbol.
    
      - **By row** – Documents are imported from or exported to an exchange file by row, or line by line.

4.  In the **Fields separator** field, select **Symbol** or **Tab** as the method to use to separate fields in the exchange format.
    

    > [!NOTE]
    > <P>You can select <STRONG>Symbol</STRONG> or <STRONG>Tab</STRONG> only if you select <STRONG>By row</STRONG> in the <STRONG>Type of exchange format</STRONG> field. If you select <STRONG>Separate by sections</STRONG> as the type of exchange format, the <STRONG>Fields separator</STRONG> field is set to <STRONG>Symbol</STRONG>.</P>



5.  In the **Symbol** field, enter the symbol to use as the separator. You can enter the symbol only if the **Type of exchange format** field is set to **By row**, and if the **Fields separator** field is set to **Symbol**.

6.  In the **Coding** field, select **DOS**, **Windows**, or **Unicode** as the code type for the exchange format.

7.  Select the **Use identifier** check box to receive the imported value based either on the **Requisite identifier** value or, if the imported field does not have the requisite identifier, on the order number.
    

    > [!NOTE]
    > <P>If you clear the <STRONG>Use identifier</STRONG> check box, you can view the values from the imported file and map the import file to the order number. If you select the <STRONG>Use identifier</STRONG> check box you can view the values based on the name of the requisite.</P>



8.  On the **General** FastTab, in the **Date - year format** field, select **Two figures** or **Four figures** as the year format.

9.  In the **Date - delimiter** field, select **Slash**, **Hyphen**, **Point**, or **No delimiter** as the character that is used to separate one number from another in a date format.

10. In the **Program-recipient** and **Program-sender** fields, enter the names of the recipient and sender of the payment files.
    

    > [!NOTE]
    > <P>If a payment is exported to a client bank from Microsoft Dynamics AX, you can enter client bank in the <STRONG>Program-recipient</STRONG> field and <STRONG>Microsoft Dynamics AX</STRONG> in the <STRONG>Program-sender</STRONG> field.</P>



11. In the **Format version** field, enter the appropriate version number for the exchange format.

12. On the **Fields** FastTab, select the new requisites to include for sorting under the exchange format code. A requisite is the information, such as bank account number, that must be included in the format.

13. On the **Setup** tab, in the **Field** field, select the requisite to include in the data exchange format that is used by the client bank. The **Sort order** field is updated with the sort order number that is used to import or export fields on the exchange file lines. You can click **Up** and **Down** to change the order. If you select the **Use identifier** check box, the **Requisite identifier** field is updated with the identifier code for the requisite.

14. In the **Participation** field, select the type of operation, from the following options:
    
      - **Export** – Export payments to a client bank.
    
      - **Import** – Import payments from a client bank.
    
      - **Export and import** – Export payments to a client bank, and import payments from a client bank.
    
      - **Import of account’s balance** – Import bank account balance statements from a client bank.

15. On the **Sections** tab, in the **Section** field, enter a section code to include in the file, such as 123. The **Sections** tab is available only if you selected **Separate by sections** in the **Type of exchange format** field.

16. In the **Section type** field, select the type of section to use to separate the data in the exchange file. The following options are available:
    
      - **Import of account balance** – This type of section contains the bank account balance information.
    
      - **Pay document** – This type of section contains information about incoming and outgoing payments.
    
      - **Exchange file borders** – This type of section contains the codes for the beginning and end of a file. If you select the **Use identifier** check box, the **Section beginning code** and **Section end code** fields are updated with the required beginning code and ending code for the section, based on the value in the **Section type** field.

## See also

[(RUS) Exchange formats of client-bank (form)](https://technet.microsoft.com/library/jj733242\(v=ax.60\))

  



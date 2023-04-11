---
title: (CHN) Set up the Chinese user interface
TOCTitle: (CHN) Set up the Chinese user interface
ms:assetid: 022a82d8-1c1d-413e-b4b0-f0b73a48253b
ms:mtpsurl: https://technet.microsoft.com/library/JJ663984(v=AX.60)
ms:contentKeyID: 49384570
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- user interface
- Chinese
audience: Application User
ms.search.region: China (PRC)
---

# (CHN) Set up the Chinese user interface 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Names and addresses of people must be entered and displayed in Chinese characters using a specified format. The address format should display the entire address on a single line.

To enter names, addresses, and numbers in Chinese characters and symbols, you must specify a default encoding format. The default Unicode type used for China is **GB18030**.

Use the following procedures to set up the default encoding format, contact names, and addresses to be displayed in Chinese characters.

## Set up the encoding format for Chinese characters

Unicode is used for encoding and processing the characters and symbols in Microsoft Dynamics AX. **GB18030** supports the Chinese character set.

1.  Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Outbound ports**.

2.  In the **Default encoding format** field, select **GB18030**.

3.  Close the form.

## Set up contact names using the Chinese format

You can use the **Name sequences** form to create a name sequence, and then use that sequence as the name format for contacts, such as vendors and customers. The Chinese name format uses the last name followed by the first name, without a separator or space between each name in the sequence. For example, if the last name of a contact is Chan and the first name is Shuh San, the contact’s name should be displayed as ChanShuhSan. After you set up the contact name format, use the **Global address book parameters** form to assign it as the default name sequence for all Chinese contacts. For more information about how to set up a default name sequence for a country/region, see [Set up global address book parameters](set-up-global-address-book-parameters.md).

You can use the **Translation** form to view the name sequence information in Chinese characters.

1.  Click **Organization administration** \> **Setup** \> **Global address book** \> **Name sequences**.

2.  Click **New** to create a new name sequence record.

3.  In the **Name sequence** field, enter a name sequence for the Chinese format. The name format for China uses the last name followed by the first name, without spaces between the two.

4.  In the **Description** field, enter a description for the name sequence. For example, you may enter China in the **Description** field.

5.  In the **First position** field, select **Last name**.

6.  In the **Second position** field, select **First name**.

7.  Close the form.

You can view how the name sequence will be displayed in the **Preview** field.

## Set up contact addresses using the Chinese format

The address format determines how addresses are displayed when you print them. In China, addresses are typically displayed in a single line, in order of largest detail to smallest. The address format that is used in China is as follows: Country, State, City, District, and Street number. After you set up the new address format, you must assign the new format to China so that it is displayed on all postal address records created for China. For more information about how to assign an address format to a country/region, see the **Set up country/region information** procedure in the [Key tasks: Set up address formats](key-tasks-set-up-address-formats.md) topic.

1.  Click **Organization administration** \> **Setup** \> **Addresses** \> **Address setup**.

2.  Select **Address format** in the left pane, and then click **New** to add a new address format for China.

3.  In the **Address format** and **Description** fields, enter an identifier, and a name for the address format. For example, you may enter CHN in the **Address format** field, and enter China in the **Description** field.

4.  On the **Configure address component** FastTab, click **New** to configure a new address component for the Chinese address format type.

5.  In the **Address application object** field, select the objects that will appear when the Chinese address format is displayed. The selection order for the Chinese address format will be as follows:
    
      - **Country/region**
    
      - **State or province**
    
      - **City**
    
      - **District**
    
      - **Street**
    
      - **ZIP/postal code**
    

    > [!NOTE]
    > <P>To rearrange the address components, click <STRONG>Up</STRONG> or <STRONG>Down</STRONG>. For more information about how to set up an address format for a country/region, see the <STRONG>Set up address formats</STRONG> procedure in the <A href="key-tasks-set-up-address-formats.md">Key tasks: Set up address formats</A> topic.</P>



6.  Close the form.

## See also

[AIF outbound ports (form)](https://technet.microsoft.com/library/hh227495\(v=ax.60\))

[Name sequences (form)](https://technet.microsoft.com/library/hh209673\(v=ax.60\))

[Translation (form)](https://technet.microsoft.com/library/hh370703\(v=ax.60\))

[Address setup (form)](https://technet.microsoft.com/library/hh209301\(v=ax.60\))

[(CHN) Import ZIP/postal codes](chn-import-zip-postal-codes.md)

  



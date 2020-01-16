---
title: (RUS) Import the Russian address classifier KLADR
TOCTitle: (RUS) Import the Russian address classifier KLADR
ms:assetid: 41723630-f8e3-4e10-b644-86eadc76effd
ms:mtpsurl: https://technet.microsoft.com/library/JJ839661(v=AX.60)
ms:contentKeyID: 50396808
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Import the Russian address classifier KLADR 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can import the Russian address classifier (KLADR) together with the address abbreviations from the KLADR database.

1.  Click **Organization administration** \> **Setup** \> **Addresses** \> **Import of addresses**.

2.  In the **Import of data** form, you can use the setup of open database connectivity (ODBC) to help you to create a new data source by using the Microsoft dBase driver. Click **ODBC setup** to open the **ODBC Data Source Administrator** form.

3.  Specify the source name and the path of the folder that contains the KLADR files.
    

    > [!NOTE]
    > <P>The required KLADR file must first be downloaded from the website of the chief scientific research computing center or GNIVC. After the new data source is saved, it is available in the <STRONG>Name of ODBC source</STRONG> field in the <STRONG>Import of data</STRONG> form.</P>



4.  In the **Name of ODBC source** field, select the data source that is linked to the file path of the KLADR files that are in \*.DBF format.

5.  In the **State** field, enter the numeric code for the state that you are importing the addresses for.

6.  Click **OK** to import the addresses.

## See also

[(RUS) Import of data (form)](https://technet.microsoft.com/library/jj711541\(v=ax.60\))

  



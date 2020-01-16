---
title: (USA) Create and register a Facebook or Twitter application
TOCTitle: (USA) Create and register a Facebook or Twitter application
ms:assetid: 9bd5492a-cd7a-4cf3-a8c1-d57821e6b6f8
ms:mtpsurl: https://technet.microsoft.com/library/JJ682098(v=AX.60)
ms:contentKeyID: 49655585
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: USA
---

# (USA) Create and register a Facebook or Twitter application 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

As part of the process for publishing retail discounts on Facebook or Twitter, you create an application on Facebook or Twitter, and then register the application with Microsoft Dynamics AX.


> [!NOTE]
> <P>This feature is not available if Microsoft Dynamics AX 2012 R3 is installed.</P>



## Create and register a Facebook application

1.  On Facebook, create a Facebook application that posts the promotion to a company page.
    

    > [!TIP]
    > <UL>
    > <LI>
    > <P>Give the application a name that reflects the name of the promotion.</P>
    > <LI>
    > <P>You can use a sample Facebook application that has ID 175147035899844 for demo purposes only.</P></LI></UL>



2.  Click **Retail** \> **Setup** \> **Parameters** \> **Retail shared parameters**. Click **Facebook**, and then, in the **Application ID** field, enter the ID of the Facebook application.

## Create and register a Twitter application

1.  Set up a Twitter application for your company at <https://dev.twitter.com/apps/new>. Logon is required.
    
    If you already have the application, go to <https://dev.twitter.com/apps>.

2.  Click **Settings**, and then make sure that you have set up a call-back URL that is set to your company’s website.

3.  Set the type of application access to **Read and Write**.

4.  Click **Retail** \> **Setup** \> **Parameters** \> **Retail shared parameters**. Click **Twitter**.

5.  In the **Consumer key** field, enter the consumer key of the Twitter application.

6.  In the **Consumer secret** field, enter the consumer secret of the Twitter application.

## See also

[(USA) About adding retail online discounts to a campaign](usa-about-adding-retail-online-discounts-to-a-campaign.md)

  



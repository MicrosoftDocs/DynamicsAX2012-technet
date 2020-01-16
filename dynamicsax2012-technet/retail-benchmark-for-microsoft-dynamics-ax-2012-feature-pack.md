---
title: Retail Benchmark for Microsoft Dynamics AX 2012 Feature Pack
TOCTitle: Retail Benchmark for Microsoft Dynamics AX 2012 Feature Pack
ms:assetid: e92ee88d-fbc1-49ca-bac6-f081270e7b33
ms:mtpsurl: https://technet.microsoft.com/library/JJ729776(v=AX.60)
ms:contentKeyID: 49564945
author: Khairunj
ms.date: 08/18/2014
mtps_version: v=AX.60
---

# Retail Benchmark for Microsoft Dynamics AX 2012 Feature Pack 


_**Applies To:** Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In 2012, Microsoft conducted a benchmark on Microsoft Dynamics AX 2012 to measure the performance and scalability characteristics of the Microsoft Dynamics AX 2012 Feature Pack retail solution in a simulated retail scenario. The benchmark showcases the ability of Microsoft Dynamics AX 2012 to handle various specialized loads concurrently, without compromising performance and scalability on critical business processes. The benchmark includes many functional scenarios across different client and integration technologies, thereby providing a view of retail back-end scenarios.

The following scenarios were executed to complete the benchmark:

  - Trickle feed of point of sale (POS) transactions from stores

  - End-of-day processing of POS transactions:
    
      - Inventory reservations were made for the imported transactions.
    
      - Imported POS transactions were consolidated and aggregated, and then transferred to statements in a peak load situation.
    
      - Statements were processed and transferred to sales orders, and financial updates were posted.

The scenarios generate load on an instance of Application Object Server (AOS).

The benchmark showcases that the end-of-day processing for 800,000 POS transactions was completed within four hours and utilizes the batch framework effectively. This means that even higher volumes can easily be handled by scaling up or out on the AOS tier and by scaling up on the Database tier.

We have published the following two papers about the Retail benchmark:

  - [Retail benchmark for multiple retail workloads detailed results](https://go.microsoft.com/fwlink/?linkid=266254) This paper provides detailed results of the Retail benchmark testing, and can be downloaded from CustomerSource and PartnerSource.

  - [Retail benchmark summary results](https://go.microsoft.com/fwlink/?linkid=266255) This paper provides a summary of the Retail benchmark testing, and can be downloaded from CustomerSource and PartnerSource.

For more information about Retail performance, see [Retail Performance for Microsoft Dynamics AX 2012](retail-performance-for-microsoft-dynamics-ax-2012.md).

  



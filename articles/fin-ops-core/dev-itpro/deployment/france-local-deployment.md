---
# required metadata

title: Finance and Operations apps in France
description: This topic provides information about the availability of Finance and Operations apps in France's data centers.
author: tfehr
ms.date: 05/17/2021
ms.topic: article
ms.prod: 
ms.technology: 

# optional metadata

# ms.search.form: 
# ROBOTS: 
audience: Application User
# ms.devlang: 
ms.reviewer: sericks
# ms.tgt_pltfrm: 
# ms.custom: 
# ms.assetid: 
ms.search.region: France
# ms.search.industry: 
ms.author: tfehr
ms.search.validFrom: 2019-07-18
ms.dyn365.ops.version:  

---

# Finance and Operations apps in France

[!include [banner](../includes/banner.md)]

Finance and Operation application, Finance, Commerce and Supply Chain, is available in France Azure region This deployment option serves customers in regulated industry and commercial organizations that do business with entities in France that require local data residency. 

The deployment of the Dynamics 365 services in France is built upon the foundational principles of security, privacy, compliance, transparency and reliability. This deployment provides French organizations a complete cloud infrastructure and platform, and familiar productivity and business application tools. All of this means that customer data stays resident within France, including the telemetry.

**Provisioning**

The prerequisite to deploy to France is to use the localized version of Lifecycle Services (LCS), referred to as [Go Local LCS, FR.LCS.Dynamics.com](https://fr.lcs.dynamics.com/Logon/Index). If you’re interested in local deployment to a specific region, you must first contact Microsoft to learn more about the onboarding process and the process to whitelisted (customer and partner).

**Features not available**

Due to certain technical dependencies, the following features listed are not available for general availability in Go Local deployment. However Microsoft strives to maintain functional parity between our commercially available service and Dynamics 365 offerings in France. For more information about these exceptions or for questions about services in France, contact [Microsoft Dynamics 365 Support](https://dynamics.microsoft.com/support/).

- Alert Service for Dynamics Regulatory Alert Submission
- APQC Business process modeler (BPM) Library: no Corporate libraries are available. For each go local regions, LCS only published the Getting started library and the last published APQC, which customer can copy to their project library for edit and publish as the corporate library.
- Dynamics 365 Translation Service overview is not available.
- Electronic reporting (ER) overview assets : Shared Asset Library is empty but it can be manually uploaded from the LCS global asset library. Mitigation is to run a script by Microsoft Engineering.
- Embedded Power Bi dashboard is not available. General Availability is later 2021.
- Environment Monitoring of Lifecycle Services does not expose the same telemetry as Global LCS.
- Planning Optimization is not available in France
- Human Resource application
- Project Operation application
- Fraud Protection application
- Production Environment Update Cadence for Auto Update is missing in the UI - this feature should be available in April 2022 
- Azure Build Pipeline using hosted Agents: Nuggets package from LCS library not available
- Some Self Service from LCS are not available such as "Service Request Sandbox to Production" or "Enable Access" for JIT access to Tier 2.
- Cloud Scale Unit for Commerce, WareHouse and Manufacturing.
- Local Business Data deployment


**Additional resources**

- This page includes information and links to resources that can help you set up legal entities with a primary address in France: https://docs.microsoft.com/en-us/dynamics365/finance/localizations/france
- Product availability per country and workload: https://dynamics.microsoft.com/en-us/availability-reports/


[!INCLUDE[footer-include](../../../includes/footer-banner.md)]

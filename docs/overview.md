---
title: Orlig Solution Overview
---
1. **Solution Narrative**  
2. **Solution Overview** 

The proposed Orlig CRM solution provides a centralized platform for managing customer enquiries and service requests across \[Customer Name]. Customers may engage the business through \[Fill in Channels]. Regardless of the originating channel, all interactions are standardized and captured as cases within Orlig CRM, creating a single system of record that ensures consistency, visibility, and governance throughout the service lifecycle. 

 Once a case is created, Orlig CRM orchestrates the appropriate fulfilment workflow by triggering automated processing via \[Fill in integration layer] where applicable, with clear handling of success and failure outcomes.  

Fulfilment results are returned to Orlig CRM to update case status and for SLA tracking, enabling automated customer notifications for successful completion and follow-up and extension where additional fulfilment is required. This end-to-end orchestration ensures efficient service delivery while maintaining operational control and compliance. 

\[Put in a overview flow diagram] 

1. **Modular Architecture for Long-Term Stability** 

Orlig CRM is designed using a modular, layered architecture that separates user interface, business logic, integrations, automation services, and data access into distinct components. This approach ensures that system enhancements or version upgrades can be introduced in a controlled manner. 

In most upgrade scenarios, changes are confined to the **Domain Logic** layer, allowing Orlig to introduce new capabilities or regulatory updates without affecting existing user interfaces, integrations, or data structures. This minimizes regression risk, reduces upgrade effort, and ensures long-term platform stability for the business.

![](/img/solutionoverview.png)

<iframe width="560" height="315" src="https://www.youtube.com/embed/XmV2k9JKv5M?si=gmDFgbK0vhOiB_O0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

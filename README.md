# Microsoft-Sentinel

**Overview:** Repository for demonstrating security incident management with Microsoft Sentinel.

**Prerequisites:**
✅ Active Azure subscription with Policy access (Free account, Student account, or paid subscription).
✅ Owner, Contributor, or Resource Policy Contributor role in the subscription.
✅ Understanding Azure Policy concepts (definitions, assignments, and initiatives).
✅ Access to resource groups or individual resources within the subscription.

**High-Level Steps with Explanations:**

 **1. Configure Microsoft Sentinel:** I began by enabling Microsoft Sentinel on an existing Azure Log Analytics workspace. This step set the foundation for collecting and analyzing security data from various sources. Setting up Sentinel was straightforward, and it provided a centralized hub for managing my organization's security monitoring and incident response efforts.

 **2. Connect Data Sources:** I connected essential data sources, such as Azure Active Directory and Azure Activity Logs, to Microsoft Sentinel. These integrations allowed me to gather logs and events from my environment, ensuring I had comprehensive visibility into user activities, resource operations, and potential threats.

 **3. Create and Customize Analytics Rules:** I configured analytics rules to detect unusual activities or potential threats in my environment. For example, I created rules to flag anomalous sign-ins and unauthorized access attempts. This task helped me understand how Sentinel proactively generates alerts based on predefined criteria to enhance threat detection.

 **4. Investigate Incidents:** I used Sentinel’s investigation tools to analyze generated incidents. By diving deep into the alerts, I identified potential attack vectors, evaluated their impact, and determined how to respond effectively. This hands-on task demonstrated Sentinel's capability to visualize the relationships between entities in an incident.

 **5. Configure Playbooks for Automated Responses:** I created automated response workflows using playbooks powered by Azure Logic Apps. For example, I configured a playbook to notify administrators via email and block suspicious IP addresses when specific threats were detected. Automating responses significantly reduced the time it takes to address security issues.

**Reference Link(s):**
[* https://microsoftlearning.github.io/AZ-104-MicrosoftAzureAdministrator/Instructions/Labs/LAB_02b-Manage_Governance_via_Azure_Policy.html](https://microsoftlearning.github.io/AZ500-AzureSecurityTechnologies/Instructions/Labs/LAB_10_Microsoft%20Sentinel.html)

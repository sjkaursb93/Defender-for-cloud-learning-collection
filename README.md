# Microsoft Defender-for-cloud-learning-collection

## Introduction
Microsoft Defender for cloud is a cloud native application protection platform (CNAPP) which safeguards the cloud based applications from various threats and vulnerabilities.<br>
What does it cover? How much it costs? How it helps to meet regulatory compliance? This learning collection will provide you answers to all these questions and more.<br>
Keep in mind, the principles of [Zero Trust](https://learn.microsoft.com/en-us/azure/security/fundamentals/zero-trust) and [Shared Responsibility](https://learn.microsoft.com/en-us/azure/security/fundamentals/shared-responsibility) <br>
In addition to setting up Microsoft Defender for Clod [use this article](https://learn.microsoft.com/en-us/azure/security/fundamentals/best-practices-and-patterns) to understand the security best practices to use when you're designing, deploying, and managing your cloud solutions by using Azure. <br>

## Security Recommendations and Security Alerts
The two main things you'll be looking for when setting up Microsoft Defender for cloud is Security Recommendations and Alerts.<br>

**Security Recommendations** play a crucial role in enhancing your organization's security posture. The recommendations are based on assessments of your resources and workloads against built-in custom security standards. Before getting started with the recommendations assessments, I have always referred to [Recommendations Reference ](https://learn.microsoft.com/en-us/azure/defender-for-cloud/recommendations-reference)to understand the baseline which is based on Microsoft cloud security benchmark. <br>
Defender for cloud now also provides [Devops Recommendations](https://learn.microsoft.com/en-us/azure/defender-for-cloud/recommendations-reference-devops), if you connect Azure Devops, GitHub, GitLab with Defender. <br>
Note if you have multi-cloud architecture, Defender for Cloud can be used to assess AWS and GCP environments. Here are additional recommendations links:
- [AWS Security Recommendations](https://learn.microsoft.com/en-us/azure/defender-for-cloud/recommendations-reference-aws)
- [GCP Security Recommendation](https://learn.microsoft.com/en-us/azure/defender-for-cloud/recommendations-reference-gcp)

**Security Alerts** 
Microsoft Defender for Cloud generates security alerts when it detects potential threats in your Azure, hybrid or multi-cloud environments. These alerts are part of workload protection plans and are triggered by advanced detections when you enable Defender plans for specific resource types. Similar to Security recommendations, I always refer to the [Security Alerts Reference](https://learn.microsoft.com/en-us/azure/defender-for-cloud/alerts-reference).


## Defender for Cloud Plans
The next step I recommend to see what different plans are available. The different plans are specific to the type of workload you want to protect, such as servers, databases,storage accounts, app services and more. You can customize your security with the right cloud workload protection plan for your resources in Defender for Cloud portal. <br>
From the Microsoft Defender for Cloud blade, click on environment settings, click on  your subscription. You'll see the screen as below. The details, settings, price will provide you additional details. 
<img width="893" alt="image" src="https://github.com/sjkaursb93/Defender-for-cloud-learning-collection/assets/112006044/353f8aae-a45f-4cba-ad73-58569fba9ddd">

For instance, Defender for CSPM, is one of Microsoft Defender for Cloud's main pillars. [Cloud security posture management (CSPM)](https://learn.microsoft.com/en-us/azure/defender-for-cloud/concept-cloud-security-posture-management)(CSPM), provides detailed visibility into the security state of your assets and workloads, and provides hardening guidance to help you efficiently and effectively improve your security posture. Follow the subsequent links to learn more about different defender plans. <br>

**Once you have set up Defender, these are the next steps:**

### Workbooks
Workbooks are a common feature among, Defender, Azure Monitor and Sentinel. It is extremely helpful to track your organization's security posture. There are many pre-defined workbooks available which can help you get started. For instance, [Coverage Workbook](https://learn.microsoft.com/en-us/azure/defender-for-cloud/custom-dashboards-azure-workbooks#coverage-workbook) and [Vulnerability Assessment Findings Workbooks](https://learn.microsoft.com/en-us/azure/defender-for-cloud/custom-dashboards-azure-workbooks#vulnerability-assessment-findings-workbook)

### Secure Score
The [secure score](https://learn.microsoft.com/en-us/azure/defender-for-cloud/secure-score-security-controls) helps improve the cloud security posture. It assess your current security situation and aggregates into a single score. The higher the score, the lower the identified risk is. In the secure score tab of the security recommendations, you can see the impact on secure score, once the security recommendation is implemented. There is a [pre-defined workbook](https://learn.microsoft.com/en-us/azure/defender-for-cloud/custom-dashboards-azure-workbooks#secure-score-over-time-workbook), which helps you keep track of secure score over time.

### Regulatory Compliance
Along with [Policy](https://learn.microsoft.com/en-us/azure/governance/policy/concepts/regulatory-compliance), Defender for cloud can be used to stay compliant to a regulatory standard/benchmark. The [regulatory compliance](https://learn.microsoft.com/en-us/azure/defender-for-cloud/regulatory-compliance-dashboard) dashboard shows compliance state and scope of improvements. From workbooks perspective,the [compliance over time workbook](https://learn.microsoft.com/en-us/azure/defender-for-cloud/custom-dashboards-azure-workbooks#compliance-over-time-workbook) can help you keep track of your compliance posture.

### Workflow Automation
A common scenario: "You have enabled defender for cloud. You see, recommendations and alerts, how to do the incident response and management?" The answer is [workflow automation](https://learn.microsoft.com/en-us/azure/defender-for-cloud/workflow-automation). It uses logic apps. You can trigger a logic app, for a defender for cloud recommendation, security alert or regulatory compliance assessment. Within the logic you can do the integration with tools such as Jira, Teams, Outlook etc.

## Other Blogs
- Keep an eye on  [What's new in Microsoft Defender for Cloud](https://learn.microsoft.com/en-us/azure/defender-for-cloud/release-notes?WT.mc_id=Portal-Microsoft_Azure_Security#business-model-and-pricing-updates-for-defender-for-cloud-plans) to stay up to date with the recent developments.
- [Azure Resource Graph sample queries](https://learn.microsoft.com/en-us/azure/defender-for-cloud/resource-graph-samples?tabs=azure-cli)
- [Common Questions - General](https://learn.microsoft.com/en-us/azure/defender-for-cloud/faq-general)
- [Common Questions - Defender for Containers](https://learn.microsoft.com/en-us/azure/defender-for-cloud/faq-defender-for-containers#what-are-the-options-to-enable-the-new-plan-at-scale-)
- [Common Questions - Regulatory Compliance](https://learn.microsoft.com/en-us/azure/defender-for-cloud/faq-regulatory-compliance)
- [Microsoft Defender for Cloud Blog](https://techcommunity.microsoft.com/t5/microsoft-defender-for-cloud/bg-p/MicrosoftDefenderCloudBlog)

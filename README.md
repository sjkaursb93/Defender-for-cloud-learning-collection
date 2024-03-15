# Microsoft Defender-for-cloud-learning-collection

## Introduction
Microsoft Defender for cloud is a cloud native application protection platform (CNAPP) which safeguards the cloud based applications from various threats and vulnerabilities.<br>
What does it cover? How much it costs? How it helps to meet regulatory compliance? This learning collection will provide you answers to all these questions and more.<br>
Keep in mind, the principles of [Zero Trust](https://learn.microsoft.com/en-us/azure/security/fundamentals/zero-trust) and [Shared Responsibility](https://learn.microsoft.com/en-us/azure/security/fundamentals/shared-responsibility) <br>
In addition to setting up Microsoft Defender for Clod [use this article](https://learn.microsoft.com/en-us/azure/security/fundamentals/best-practices-and-patterns) to understand the security best practices to use when you're designing, deploying, and managing your cloud solutions by using Azure. <br>

## Security Recommendations and Security Alerts
The two main things you'll be looking for when setting up Microsoft Defender for cloud is Security Recommendations and Alerts.<br>

**Security Recommendations** play a crucial role in enhancing your orgnization's security posture. The recommendations are based on assessments of your resources and workloads agains built-in custom security standards. Before getting started with the recommendations assessments, I have always referred to [Recommendations References ](https://learn.microsoft.com/en-us/azure/defender-for-cloud/recommendations-reference)to understand the baseline which is based on Microsoft cloud benchmark. <br>
Defender for cloud now also provides [Devops Recommendations](https://learn.microsoft.com/en-us/azure/defender-for-cloud/recommendations-reference-devops), if you connect Azure Devops, GitHub, GitLab with Defender. <br>
Note if you have multi-cloud architecture, Defender for Cloud can be used to assess AWS and GCP enviornments. Here are additional recommendations links:
- [AWS Security Recommendations](https://learn.microsoft.com/en-us/azure/defender-for-cloud/recommendations-reference-aws)
- [GCP Security Recommendation](https://learn.microsoft.com/en-us/azure/defender-for-cloud/recommendations-reference-gcp)

**Security Alerts** - 
Microsoft Defender for Cloud generates security alerts when it detects potential threats in you Azure, hybrid or multicloud environments. These alerts are part of workload protection plans and are triggered by advanced detections when you enable Defender plans for specific resource types. Similar to Security recommendations, I always refer to the [Security Alerts Reference](https://learn.microsoft.com/en-us/azure/defender-for-cloud/alerts-reference) list  


## Defender for Cloud Plans
The next step I recommend to see what different plans are available. The different plans are specific to the type of workload you want to protect, such as servers, databases,stortage accounts, app services and more. You can customize your security with the right cloud workload protection plan for your resources in Defender for Cloud portal. <br>
From the Microsoft Defender for Cloud blade, click on envrionment settiings, click on  your subscription. You'll see the screen as below. The details, settings, price will provide you additional details. 
<img width="893" alt="image" src="https://github.com/sjkaursb93/Defender-for-cloud-learning-collection/assets/112006044/353f8aae-a45f-4cba-ad73-58569fba9ddd">

Here is also a brief summary of different defender plans to help you get started. <br>
### CSPM - Cloud Security Posture Management - 
One of Microsoft Defender for Cloud's main pillars is [cloud security posture management (CSPM)](https://learn.microsoft.com/en-us/azure/defender-for-cloud/concept-cloud-security-posture-management). CSPM provides detailed visibility into the security state of your assets and workloads, and provides hardening guidance to help you efficiently and effectively improve your security posture.




## What's next


### Other Blogs
- Keep an eye on  [What's new in Microsoft Defender for Cloud](https://learn.microsoft.com/en-us/azure/defender-for-cloud/release-notes?WT.mc_id=Portal-Microsoft_Azure_Security#business-model-and-pricing-updates-for-defender-for-cloud-plans) to stay up to date with the recent developments.
- [Azure Resource Graph sample queries](https://learn.microsoft.com/en-us/azure/defender-for-cloud/resource-graph-samples?tabs=azure-cli)

- [Microsoft Defender for Cloud Blog](https://techcommunity.microsoft.com/t5/microsoft-defender-for-cloud/bg-p/MicrosoftDefenderCloudBlog)

IBM Cloud Logs is a scalable logging service that persists logs and provides users with capabilities for querying, tailing, and visualizing logs.

Logs are comprised of events that are typically human-readable and have different formats, for example, unstructured text, JSON, delimiter-separated values, and key-value pairs. You can use the events to investigate abnormal activity and critical actions and to comply with regulatory audit requirements. IBM® Power® Virtual Server automatically generates events so that you can track activity on your service.

For a complete list of all IBM Cloud Logs events for IBM Power Virtual Server, visit [this page](https://cloud.ibm.com/docs/power-iaas?topic=power-iaas-at-events){target="_blank"}

!!! note "IBM Cloud Logs replaces IBM Log Analysis and IBM Cloud Activity Tracker"

    As of 30 March 2025 the IBM Log Analysis and IBM Cloud Activity Tracker services are no longer supported. IBM Cloud Logs replaces these two services. For information about IBM Cloud Logs, see the [IBM Cloud Logs documentation](https://cloud.ibm.com/docs/cloud-logs){target="_blank"}. Also it is important to note that while IBM Cloud Activity Tracker is being deprecated, activity tracker events will be supported in both the new IBM Cloud Logs service and with the existing IBM Cloud Activity Tracker Event Routing service. See [Deprecation FAQ](https://cloud.ibm.com/docs/activity-tracker?topic=activity-tracker-deprecation_faq){target="_blank"} for more details. You may also refer to [this blog](https://community.ibm.com/community/user/cloud/blogs/marisa-lopez-de-silanes/2025/03/03/migrating-your-activity-tracker-instances-to-cloud){target="_blank"} for guidance on migrating your Activity Tracker instances to Cloud Logs.

For this demonstration guide, an IBM Cloud Logs instance is already provisioned. This instance tracks activities for the resources that are part of the PowerVS-L3 resource group in the shared cloud account. Your user ID has permission to open and view the IBM Cloud Logs dashboard.

In the steps that follow, learn how to:

- Access the IBM Cloud Logs instance by using the IBM Cloud portal
- Open the IBM Cloud Logs dashboard
- Explore activities that are related to the PowerVS resources in this environment

Note, this demonstration guide does not provide detailed information on provisioning, configuring, and customizing IBM Cloud Logs, nor does it provide details on the meaning of individual activities.

1. Click the IBM Cloud portal **hamburger (A)** menu, expand the **Observability (B)** menu and click **Logging (C)**.
   ![image](https://github.com/user-attachments/assets/0f610b4e-bd70-45c2-acbf-e94818835d76)   
   ![image](https://github.com/user-attachments/assets/5e8477dc-44be-4b04-876c-d740f2d2e99b)

2. You will be taken to the Observability page. Expand **Logging (A)** menu and click **Instances (B)**.
   ![image](https://github.com/user-attachments/assets/8f9d0c9b-3d3c-4cc6-bab6-218dad533d52)


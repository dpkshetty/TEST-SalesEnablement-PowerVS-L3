IBM Cloud Logs is a scalable logging service that persists logs and provides users with capabilities for querying, tailing, and visualizing logs.

Logs are comprised of events that are typically human-readable and have different formats, for example, unstructured text, JSON, delimiter-separated values, key-value pairs, and so on. The IBM Cloud Logs service can manage general purpose application logs, platform logs, or structured audit events. IBM Cloud Logs can be used with logs from both IBM Cloud services and customer applications.

!!! note "IBM Cloud Logs replaces IBM Log Analysis and IBM Cloud Activity Tracker"

    As of 30 March 2025 the IBM Log Analysis and IBM Cloud Activity Tracker services are no longer supported. IBM Cloud Logs replaces these two services. For information about IBM Cloud Logs, see the [IBM Cloud Logs documentation](https://cloud.ibm.com/docs/cloud-logs){target="_blank"}. Also it is important to note that while IBM Cloud Activity Tracker is being deprecated, activity tracker events will be supported in both the new IBM Cloud Logs service and with the existing IBM Cloud Activity Tracker Event Routing service. See [Deprecation FAQ](https://cloud.ibm.com/docs/activity-tracker?topic=activity-tracker-deprecation_faq){target="_blank"} for more details.

TODO: For this demonstration guide, an IBM Cloud Logs instance is already provisioned. This instance tracks activities for the resources that are part of the PowerVS-L3 resource group in the shared cloud account. Your user ID has permission to open and view the IBM Cloud Logs dashboard.

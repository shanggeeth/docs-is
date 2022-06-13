# Viewing Alerts

Follow the steps below to view the authentication-related alerts generated by WSO2 Identity Server.

!!! tip

    **Before you begin**
    
    1. [Configure](../../learn/elk-analytics-installation-guide) ELK-based analytics in WSO2 IS.
    2. [Configure](../../learn/elk-analytics-installation-guide) analytics dashboard.

1. Login to Kibana and navigate to `Dashboards > Alert Dashboard`.
2. Select a timer interval to filter the alerters within a given duration, e.g., 1 day.
   All the alerts that are generated during this time interval appears.
    - **Abnormal long session alert**
    <img src="../../assets/img/learn/elk-analytics/alerting/elk-alerting-5.png" alt="Long session alert">
    - **Suspicious login alert**
    <img src="../../assets/img/learn/elk-analytics/alerting/elk-alerting-2.png" alt="Suspicious login alerts">
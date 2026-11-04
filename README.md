# Azure-Defender-for-Cloud-Microsoft-Sentinel-Security-Monitoring-Lab


## 1. Overview

This lab explored Microsoft Defender for Cloud, Microsoft Sentinel, Windows Security Events, and Network Watcher.

The goal was to understand how Azure collects security and network activity logs and how those logs can support security monitoring and threat detection.

## 2. Microsoft Sentinel – Setting Up Security Event Logs

To configure security event collection in Microsoft Sentinel:

1. Open Microsoft Sentinel.
2. Navigate to **Content Management**.
3. Select **Content Hub**.
4. Find the Windows Security Events solution.
5. Select the features needed and install the solution.

I selected Windows Security Events to explore how Windows activity can be collected and monitored for security purposes.

## 3. Configuring Data Collection

After installing the Windows Security Events solution, I explored its management settings.

By selecting **Manage**, I could access the configuration options for Azure Monitor Agent (AMA) and automated data collection.

These settings help determine which Windows security events are collected and sent to the Log Analytics Workspace.

## 4. Verifying Virtual Machine Extensions

To verify the configuration:

1. Navigate to Virtual Machines in the Azure Portal.
2. Select the virtual machine.
3. Open **Extensions + applications**.
4. Review the installed extensions.

The Azure Monitor Agent should appear if it was successfully installed and configured.

The collected events can then be checked in the associated Log Analytics Workspace.

## 5. Microsoft Defender for Cloud – Cloud Security Settings

I explored the cloud security settings in Microsoft Defender for Cloud.

Adjusting these settings involved selecting the security features needed and saving the configuration.

Defender for Cloud provides security recommendations and helps identify potential security risks across cloud resources.

## 6. Azure Network Watcher – Flow Logs

I also explored Network Watcher and its flow logging capabilities.

Flow logs help capture information about network traffic moving through supported Azure network resources.

**Steps explored:**

1. Open Network Watcher.
2. Navigate to Flow Logs.
3. Select Create.
4. Choose the appropriate network resource.
5. Select the required configuration fields.
6. Continue through the setup process.
7. Configure Traffic Analytics to process traffic information.

I explored setting the Traffic Analytics interval to 10 minutes, which can be adjusted depending on monitoring requirements.

## 7. What I Learned

This lab helped me understand how different Azure security services work together.

- **Microsoft Defender for Cloud:** Helps identify cloud security risks and provides security recommendations.
- **Microsoft Sentinel:** Collects and analyzes security events to identify potential threats.
- **Azure Monitor Agent (AMA):** Collects configured data from virtual machines.
- **Windows Security Events:** Provides visibility into Windows system and security activity.
- **Network Watcher:** Helps monitor and analyze network traffic.

## 8. Key Takeaway

I gained a better understanding of how security event collection and network monitoring support cloud security. I also learned how Azure Monitor Agent connects virtual machine activity to centralized logging, allowing security teams to investigate events and monitor potential threats.

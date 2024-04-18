# SOC Alert Analyzer Workbook for Azure Sentinel
![Image Header](https://i.imgur.com/G0wn5vY.png)
## Overview
This Azure Sentinel workbook is designed to monitor and analyze security alerts across multiple workspaces. It features parameters to select specific workspaces and alert names, and includes detailed queries for alert details, incident classifications, and entity-related data (e.g., accounts, hosts, and addresses), using visualizations like pie charts and bar charts to represent the data.

## Features
- **Entity Analysis**: Extensive entity parsing from alerts to extract and analyze entities like accounts and hosts, including top entities involved in incidents.
- **Alert Detail Visualization**: Provides detailed insights into specific security alerts, including the alert provider, associated tactics and techniques, and a comprehensive description.
- **Time-Based Data Aggregation**:  Aggregates data over selectable time ranges, providing insights into alert frequency over time with the ability to render this data in time-chart visualizations.

## Getting Started

### Prerequisites
- Azure Sentinel environment setup.
- Permission to access and create workbooks within Azure Sentinel.

### Installation
1. Navigate to **Azure Sentinel** > **Workbooks** in the Azure portal.
2. Click on **+ Add workbook**.
3. Select the **Advanced editor** tab and paste the JSON configuration for the SOC Entity Triage workbook within the Gallery template section.
4. Save the workbook to make it available in your Azure Sentinel environment.

### Usage
- Open the SOC Alert Analysis workbook from the Azure Sentinel > Workbooks gallery.
- Select a workspace, the alerts to analyze, and the timeframe you are looking within. 
- Use the interactive controls to filter by time range and other parameters relevant to your analysis.

![Workbook Preview1](https://i.imgur.com/EM3s6MO.png)

![Workbook Preview2](https://i.imgur.com/XNSaMSr.png)

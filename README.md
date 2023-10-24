# Executive Cost Report
![image](https://github.com/joelmsherman/Executive-Cost-Dashboard/blob/master/ExecutiveCostReport.png)

## Background
Ryan & Sons (R&S) is a major firm in the construction equipment supply industry, with manufacturing operations in both North America and Europe. To remain competitive, R&S executives needed a way of monitoring their major product manufacturing costs, and to keep tabs on their overall share of the market.  R&S finance staff prepared monthly reports using data they culled from multiple systems.  The process was cumbersome and inefficient. 

## Project Objectives
This project set out to integrate R&S cost data across the company's facilities, products, and product classes into one solution. The solution allows executives to view monthly, year-to-date, and estimated full year costs for its major products, along with variances between actual and planned costs.  Executives can easily view cost variances within a particular month, or over time by year.  The solution also connects to an industry association database API to allow B&S executives to monitor market share over time.

## Report
A link to the live report is available [here](https://app.powerbi.com/view?r=eyJrIjoiMjk4ZmE0ZmYtMmJmYy00MmFjLTg3OGUtODRjYjNhOGUxYWE3IiwidCI6IjEwMmY4MzcyLTBlMWUtNDFhMy04ZWU4LTZhOTQ5NzAyZjcxNCJ9).

## Administration & Governance

### Workspace
My Workspace

### Distribution
Publish to web

### Sensitivity Label
Public

### Permissions
Public

## Repository Organization
The repository is organized into the following folders:

### 1. Data Pipeline
Storage of all SQL scripts governing the ETL process from source system to warehouse.

### 2. ExecutiveCosts.Dataset
A collection of files and folders that represent a Power BI dataset. It contains some of the most important files you're likely to work on, like model.bim. To learn more about the files and subfolders and files in here, see [Project Dataset folder](https://learn.microsoft.com/en-us/power-bi/developer/projects/projects-dataset).

### 3. ExecutiveCosts.Report
A collection of files and folders that represent a Power BI report. To learn more about the files and subfolders and files in here, see [Project report folder](https://learn.microsoft.com/en-us/power-bi/developer/projects/projects-report).

### 4. .gitignore
Specifies intentionally untracked files Git should ignore. Dataset and report subfolders each have default git ignored files specified in .gitIgnore:

* Dataset
    - .pbi\localSettings.json
    - .pbi\cache.abf

* Report
    - .pbi\localSettings.json

In addition to these, all client project docs (project plans, sketches, wireframes, etc), data and ux artifacts are ignored.

### 5. ExecutiveCosts.pbip
The PBIP file contains a pointer to a report folder, opening a PBIP opens the targeted report and model for authoring. For more information, refer to the [pbip schema document](https://github.com/microsoft/powerbi-desktop-samples/blob/main/item-schemas/common/pbip.md).
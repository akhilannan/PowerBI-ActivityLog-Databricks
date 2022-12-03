# Introduction
This includes databricks python notebook which Extract data from [Power BI Activity Log](https://learn.microsoft.com/en-us/power-bi/admin/service-admin-auditing#use-the-activity-log) in an incremental fashion and create a delta table on top.

# Extract Power BI Activity Logs
This is the main notebook which triggers the job.

# Common Functions
This notebook will be called by the main notebook, for creating various reusable functions.
# Exercise 4: Documenting Query Parameters

Practice documenting query parameters. In this exercise, I work for a made-up company called BugSquisher, which makes software to track bugs. For quality assurance, they have an API that lets you make bugs and handle them. Here is a chart I made based on what a developer wrote down.

| Parameter| Description | Type | Notes|
|---|---|---|
| startDate | Date bug was created | Date | Format: YYYY-MM-DD. The default is the earliest recorded bug.| 
| endDate | The end date for when the bug was made. | Date | Optional| Format: YYYY-MM-DD. The default is the earliest recorded bug. |
| priority | Priority level | Integer | Number ranging from 1 to 4, with 1 being the highest priority.|
| severity | Severity level | Integer | Number ranging from 1 to 4, with 1 being the most severe.|
| status | The bug's current status. | String | Valid values include: open, closed, duplicate, and notabug. |
| start | The starting index for page numbers. | Number | The first bug on the list is number zero. | 
| total | The total number of bugs to show on each page. | Number |  | 
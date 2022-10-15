## Step 1: One day's forecast.
| Element | Description | Type | Notes |
|---|---|---|---|
|2015-09-01| Sunny day with a high of 22 degrees and a low of 20 degrees | Daily weather | No danger |

This table contains information about the daily forecast for this particular day in 2015.

## Step 2: Three-day forecast
| Date | Temperature range from low to high | Wind Speed| Danger | Outlook|
|---|---|---|---|---|
|2015-09-01|20 to 22|12|false|Sunny|
|2015-09-02|17 to 21|15|false|Overcast|
|2015-09-03|18 to 20|13|false|Raining|

Please note that the longitude and latitude for the entire object are 47.60 and 122.33 degrees, respectively.

## Step 3: Meeting Request
| Element | Description |Type | Notes|
|---|---|---|---|
|Time| Date and Time of Forecast | Integer | Format is YYYY-MO-DD |
|Duration| Duration of the weather event | String | Time in minutes and hours |
|Location| Meeting Location | String | Location by building and room number |
|Reminder| when someone is informed of the meeting | Integer | time in minutes |
|Invitees| Emails of invited guests | String | Emails in quotes and separated by commas|

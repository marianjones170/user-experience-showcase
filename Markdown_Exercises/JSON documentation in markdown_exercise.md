## Step 1: One day's forecast.
<<<<<<< HEAD
<code>{
    "date": "2015-09-01", 
    "description": "sunny", 
    "maxTemp": 22, 
    "minTemp": 20, 
    "windSpeed": 12, 
    "danger": false
}</code>
=======
``{``
``"date": "2015-09-01",`` 
``"description": "sunny", ``
``"maxTemp": 22, ``
``"minTemp": 20, ``
``"windSpeed": 12, ``
``"danger": false``
``} ``

>>>>>>> fe7fa41014568b4dc428c316a17e2506347a0eea
| Element | Description | Type | Notes |
|---|---|---|---|
|2015-09-01| Sunny day with a high of 22 degrees and a low of 20 degrees | Daily weather | No danger |

This table contains information about the daily forecast for this particular day in 2015.

## Step 2: Three-day forecast
<<<<<<< HEAD
{
    "longitude": 47.60, 
    "latitude": 122.33, 
    "forecasts": [
        {
            "date": "2015-09-01", 
            "description": "sunny", 
            "maxTemp": 22, 
            "minTemp": 20, 
            "windSpeed": 12, 
            "danger": false
        }, 
        {   
            "date": "2015-09-02", 
            "description": "overcast", 
            "maxTemp": 21,
            "minTemp": 17, "windSpeed": 15,
            "danger": false 
        },
        {
            "date": "2015-09-03",
            "description": "raining",
            "maxTemp": 20,
            "minTemp": 18, 
            "windSpeed": 13, 
            "danger": false
        }               
    ]
}
=======
``{
    ``"longitude": 47.60, ``
    ``"latitude": 122.33, ``
    ``"forecasts": [``
       `` {``
           `` "date": "2015-09-01", ``
          ``  "description": "sunny", ``
            ``"maxTemp": 22, ``
            ``"minTemp": 20, ``
            ``"windSpeed": 12, ``
            ``"danger": false``
       `` }, ``
       `` {``
            ``"date": "2015-09-02", ``
            ``"description": "overcast", ``
           `` "maxTemp": 21,``
            ``"minTemp": 17, ``
            ``"windSpeed": 15,``
            ``"danger": false ``
        ``},``
        ``{``
           `` "date": "2015-09-03", ``
           `` "description": "raining", ``
           `` "maxTemp": 20,``
           `` "minTemp": 18, ``
           `` "windSpeed": 13, ``
           `` "danger": false``
       `` } ``
   `` ]``
``}``
>>>>>>> fe7fa41014568b4dc428c316a17e2506347a0eea

| Date | Temperature range from low to high | Wind Speed| Danger | Outlook|
|---|---|---|---|---|
|2015-09-01|20 to 22|12|false|Sunny|
|2015-09-02|17 to 21|15|false|Overcast|
|2015-09-03|18 to 20|13|false|Raining|

Please note that the longitude and latitude for the entire object are 47.60 and 122.33 degrees, respectively.

## Step 3: Meeting Request

<<<<<<< HEAD
{
    "meeting" : {
       "time": "2015-09-01 10:00",
       "duration": 60,
       "description": "2016 Strategic Planning Meeting", 
       "location": "Building 23, Room 206",
       "reminder": 15,
        "invitees": ["michael@example.com", "thelma@example.com", "david@example.com", "leon@example.com"]
    } 
}
=======
``{``
   `` "meeting" : {``
       `` "time": "2015-09-01 10:00",``
       `` "duration": 60,``
       `` "description": "2016 Strategic Planning Meeting", ``
       ``"location": "Building 23, Room 206",``
      ``  "reminder": 15,``
       `` "invitees": ["michael@example.com", "thelma@example.com", "david@example.com", "leon@example.com"]``
  ``  } ``  
``}``
>>>>>>> fe7fa41014568b4dc428c316a17e2506347a0eea

| Element | Description |Type | Notes|
|---|---|---|---|
|Time| Date and Time of Forecast | Integer | Format is YYYY-MO-DD |
|Duration| Duration of the weather event | String | Time in minutes and hours |
|Location| Meeting Location | String | Location by building and room number |
|Reminder| when someone is informed of the meeting | Integer | time in minutes |
|Invitees| Emails of invited guests | String | Emails in quotes and separated by commas|

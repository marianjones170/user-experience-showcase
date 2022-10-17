# Exercise 11: Function Documentation 2

## _Before_

### Information from the Developer Team
* safeMode(enable)
Enables or disables safe mode, depending on the parameter that is passed in. No return value.

* getPremiumMode()
Gets whether the user has paid for premium mode.

* setTimeout(timeout)
Sets the time to wait for a response before timing out. The parameter value is in milliseconds.

* newEvent(calendarId) CreatesaneweventforthespecifiedcalendarwiththeIDpassedinastheparameter. CalendarIDisa number. Returns the ID for the new event, which will be a number.

* getDirections(latitude, longitude, directionsCallback)
Latitude and longitude are numbers (degrees) for the destination location. directionsCallback is a function that is called when the directions come back from the serve r. It has a string parameter called directions which contains the directions on how to get from the current location to the destination location.
(Hint: use bold to refer to any function and variable names.)

* createTransaction(amount)
Creates a new transaction, where the amount parameter is a number in the default currency. Returns the new transaction ID, which is a String. Other functions that developers might be interested in are getTransaction and deleteTransaction.

## _And After With Added Documentation_

#### safeMode(enable)
Whether to enable or disable safe mode

**Parameters**
  * enable
  Type: Boolean
  true if in safe mode; otherwise, false.

#### getPremiumMode()
Returns whether the user has paid for premium mode.

**Returns**
  Type: Boolean
  true if user has paid for premium mode; otherwise, false.

#### setTimeout(timeout)
Sets the response timeout.

**Parameters**
  * timeout
  Type: Number
  Time before timeout, in milliseconds.

#### newEvent(calendarId)
Creates a new calendar event for the specified calendar.
**Parameters**
* calendarId
  Type: Number
  ID of the specified calendar

**Returns**
Type: number
The ID of the new event

#### getDirections(latitude, longitude, directionsCallback)
**Parameters**
* latitude
Type: Number
Latitude of destination, in degrees

* longitude
Type: Number
Longitude of destination, in degrees

### directionsCallback
Type: function
Called when when the directions come back from the server. Contains a String parameter named directions, which has the directions on how to get from the current location to the destination location.

### createTransaction(amount)
Creates a new transaction

**Parameters**
* amount
Type: number
Amount of the transaction in default currency

**Returns**
new transaction ID
Type: String
ID of the new createTransaction

**See Also:**
<u><span style="color:blue">getTransaction</u></span>
<u><span style="color:blue">deleteTransaction</u></span>

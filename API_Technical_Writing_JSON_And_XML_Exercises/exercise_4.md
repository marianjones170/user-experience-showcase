Constant/Value

| Name| Description | Type | Value |
| ---- | ---- | ---- |---- |
| productName | Product name | string | RoboBall|
| versionNumber | Product version number | number | 2.6 |
| commStop | Command code tells the RoboBall stop moving | command | 0x00|
| commMoveForward | Command tells the RoboBall to move forward | command | 0x01 |
| commMoveBackward | Command code tells the RoboBall to move backward | command | 0x02 |
| commTurnLeft | Command code tells the RoboBall to go to the left| command | 0x03 |
| commTurnRight | Command code tells the RoboBall to go to the right | command | 0x04 |
| errBadSignal | Error code means that the device is not sending a good signal to the robot | error code | 0xFF01 |
| errBadCommand | Error code message means that the robot does not understand the command | error code | 0xFF02 |
|errBatteryLow | Error code message means that the robot's battery is low | error code | 0xFF03|

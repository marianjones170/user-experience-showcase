Constant/Value

| Name| Description | Type | Value |
| ---- | ---- | ---- |---- |
| RoboBall | physical product | string | RoboBall|
| versionNumber | product version number | string | 2.6 |
| commStop | makes RoboBall stop | command | 0x00|
| commMoveForward | moves the RoboBall forward | command | 0x01 |
| commMoveBackward | moves RoboBall backward | command | 0x02 |
| commTurnLeft | sends RoboBall to the left | command | 0x03 |
| commTurnRight | sends RoboBall to the right | command | 0x04 |
| errBadSignal | robot is not getting a good signal from the device | error code | 0xFF01 |
| errBadCommand | Message means robot does not recognize the command | error code | 0xFF02 |
|errBatteryLow | means Robot's battery is low | error code | 0xFF03|

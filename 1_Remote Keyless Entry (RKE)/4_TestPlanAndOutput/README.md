## TEST PLAN AND OUTPUT
## High Level Testing

| Test ID | Description of Test case | Input| Expected Output | Actual Output | Status | 
|:-----:|:--------------------------:|:-----------------:|:---------------:|:---------:|-----|
| HL1 | Car Shall Lock |User Press Button | Car Locked|Car Locked |SUCCESS ✅| 
| HL2 | Car Shall UnLock | User Press Button | Car Unlocked |Car Unlocked| SUCCESS ✅ | 
| HL3 | Car Shall Activate/Deactivate  Alarm |User Press Button  | Alarm Activated/Deactivated|Alarm Activated/Deactivated|SUCCESS ✅| 
| HL4 | Car Shall Activate Approach Light | User Press Button  | Approach Light ON|Approach Light ON  | SUCCESS ✅ |
| HL5 |Encryption|No. of times button pressed|Random|Random|SUCCESS ✅


## Low Level Testing

| Test ID | Description of Test case | Input values | Expected Output | Actual Output | Status |  
|:-----:|:--------------------------:|:--------------:|:-----------------:|:---------------:|:---------:|
| LL1  |Test For Car Lock   |Press Button one time  |All the led's are turned ON at same time  |All the led's are turned ON at same time  |SUCCESS ✅ | 
| LL2  | Test For Car Unlock  |Press Button two times   |All the led's are turned OFF at same time  |All the led's are turned OFF at same time  |SUCCESS ✅ | 
| LL3  |Test For Car Activation/Deactivation |Press Button one times  | All the led's are turned ON in Clockwise Direction |All the led's are turned ON in Clockwise Direction | SUCCESS ✅ | 
| LL4 |Test For Car Approach lights  |Press Button three times  |All the led's are turned ON in Anticlockwise Direction | All the led's are turned ON in Anticlockwise Direction| SUCCESS ✅ | 
| LL5 |Test For Encryption |No. of times button pressed|Random|Random|SUCCESS ✅


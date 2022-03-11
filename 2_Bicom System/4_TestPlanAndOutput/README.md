## TEST PLAN AND OUTPUT
## High Level Testing

| Test ID | Description of Test case | Input| Expected Output | Actual Output | Status | 
|:-----:|:--------------------------:|:-----------------:|:---------------:|:---------:|-----|
| HL1 | Windows status shall be displayed | User Press Button | Window status (Open or Close)|Window status (Open or Close)|SUCCESS ✅| 
| HL2 | Alarm status shall be displayed | User Press Button|Alarm status|Alarm status| SUCCESS ✅ | 
| HL3 | Car Battery status shall be displayed | User Press Button | Battery status (Full or not) |Battery status (Full or not)  |SUCCESS ✅| 
| HL4 | Door status displayed |User Press Button  | Door status (Lock or Unlock)|Door status (Lock or Unlock) | SUCCESS ✅ |
| HL5 |Encryption|No. of times button pressed|Random|Random|SUCCESS ✅


## Low Level Testing

| Test ID | Description of Test case | Input values | Expected Output | Actual Output | Status | 
|:-----:|:--------------------------:|:--------------:|:-----------------:|:---------------:|:---------:|
| LL1  | Windows status |Press Button one time  |All the led's are turned ON at same time  |All the led's are turned ON at same time  |SUCCESS ✅ | 
| LL2  | Alarm status  |Press Button two times   |All the led's are turned OFF at same time  |All the led's are turned OFF at same time  |SUCCESS ✅ | 
| LL3  |Car Battery status |Press Button one times  | All the led's are turned ON in Clockwise Direction |All the led's are turned ON in Clockwise Direction | SUCCESS ✅ | 
| LL4 |Door status |Press Button three times  |All the led's are turned ON in Anticlockwise Direction | All the led's are turned ON in Anticlockwise Direction| SUCCESS ✅ | 
| LL5 |Test For Encryption |No. of times button pressed|Random|Random|SUCCESS ✅

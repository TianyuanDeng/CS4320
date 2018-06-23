## Challenge 2: Alarm Clock Use Case Diagram and Description 
Creator: Yihe Wang
[Go To Homepage](https://github.com/YiheWang/CS4320)
***
### Requirements
*It is possible to set one or two alarms. When an alarm ﬁres, it will sound some noise. The user can turn it oﬀ, or choose to “snooze”. If the user does not respond at all, the alarm will turn oﬀ itself after 2 minutes. “Snoozing” means to turn oﬀ the sound, but the alarm will ﬁre again after some minutes of delay. This “snoozing time” is pre-adjustable.* 
***
### Alarm Clock Diagram
![enter image description here](https://raw.githubusercontent.com/YiheWang/CS4320/master/week3/_Alarm%20Clock%20Use%20Case%20Diagram%20and%20Description.jpg)
***
### Description
**Change Time Display**:
User can switch between 12-hour display mode and 24-hour display mode by switching the button on or off.
 
**Set Alarm**:
 1. At all beginning, user can choose to turn on or off the alarm by switching the button on or off. 
2. There are two pre-adjust setting. One is to setting snooze time, and the other is to choose the alarm sound.
 3. There are two states after setting. One is to choose snooze mode, which means the alarm will fire again after several minutes(user set before). The other state is no response; the alarm will be firing for two minutes and turn off automatically after two minutes.
 
|| Alarm Clock Use Cases Description |
|--|-----------|
| **Scenario** | Power-up and initialize the alarm |
| **Triggering Event** | A operator turn on the alarm |
| **Actor** | Operator |
|**Related use cases**|<table> <tr><th> 12-hour display</th> <th>24-hour display</th></tr></table>|
|**Pre-condition**|Alarm turned off|
|**Post-condition**|Alarm turned on and have been set|
|**Flow of events**|<table><tr><th>Operator</th><th>System</th></tr><tr><td>1. No response <br>2. Snooze<td>1. Turn off after ringing for 2 minutes<br>2. Fire again after several minutes</tr></table> |
|**Exception**|N/A|

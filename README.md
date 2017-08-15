# babySitterKataActivity
Solution for the Kata activity focused around the Babysitter schedule.



## Test cases
1:  When the user clocks their start time before 5:00 PM, return an error.
2:  When the user clocks their start time at or after 5:00 PM, return entered value.
3:  When user clocks their end time after 4:00 AM, return an error.
4:  When user clocks their end time at or before 4:00 AM, return entered value.
5:  When both start time and end time are valid, return total pay given each time 
    a.  Pay rate from start-time to bed-time = $12/hour
    b.  Pay rate from bed-time to midnight = $8/hour
    c.  Pay rate from midnight to end-time = $16/hour
    d.  Pay rated for full hours, no fractional work
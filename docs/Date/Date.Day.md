﻿# Date.Day
Returns the day component.
***
function (optional dateTime as nullable any) as nullable any
***
# Descrition 
Returns the day component of a <code>date</code>, <code>datetime</code>, or <code>datetimezone</code> value.
      <ul>
        <li><code>dateTime</code>: A <code>date</code>, <code>datetime</code>, or <code>datetimezone</code> value from which the day component is extracted.</li>       
      </ul>
# Category 
Date
# Examples 
Get the day component of a <code>date</code>, <code>datetime</code>, or <code>datetimezone</code> value representing the date and time of 5/14/2011 05:00:00 PM.
```
Date.Day(#datetime(2011, 5, 14, 17, 0, 0))
```
> 14
***
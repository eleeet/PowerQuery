# DateTime.IsInNextSecond
Indicates whether this datetime occurs during the next second, as determined by the current date and time on the system.
> _function (optional <code>dateTime</code> as nullable any) as nullable any_

# Description 
Indicates whether the given datetime value <code>dateTime</code> occurs during the next second, as determined by the current date and time on the system.
      <ul>
      <li><code>dateTime</code>: A <code>datetime</code>, or <code>datetimezone</code> value to be evaluated.</li>
      
# Category 
DateTime
# Examples 
Determine if the second after the current system time is in the next second.
```
DateTime.IsInNextSecond(DateTime.FixedLocalNow() + #duration(0,0,0,1))
```
> true

***

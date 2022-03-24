# rrule.swift
**rrule.swift** supports recurrence rules in Swift 4  (No other 3rd-party dependencies).

be converted into swift package

How to use
------
Drag **rrule.swift** into your project. 

	let rule = rule(frequency, dtstart: dtstart, until: until, count: count, interval: interval, wkst: wkst, bysetpos: bysetpos, bymonth: bymonth, bymonthday: bymonthday, byyearday: byyearday, byweekno: byweekno, byweekday: byweekday)
	let occurrences = rule.getOccurrences()

To do
------
* Hourly
* Minutely
* Secondly

Author
------
[sdq](http://shidanqing.net)


License
-------
[MIT](https://opensource.org/licenses/MIT)

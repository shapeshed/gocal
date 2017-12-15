# GoCal

Hacking a Google Calendar terminal viewer because terminal > browser and all the other clients suck

# Features

* View your upcoming events.
* Err.. that's it. 

This is mostly hacked from the [example code][1] for viewing Google Calendar events in the terminal. 

The `column` command is used to format the output since it does a good job of that. 

    gocal | column -t -o  " |" -s ","

This gives the following output the terminal

    15/12/2017 10:30 | Standup
    15/12/2017 13:30 | Testing Call
    15/12/2017 14:00 | Boring Meeting
    15/12/2017 15:00 | On site interview with Linus Torvalds
    15/12/2017 16:00 | Monthly Staff Meeting

[1]: https://developers.google.com/google-apps/calendar/quickstart/go

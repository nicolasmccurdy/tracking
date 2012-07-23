#tracking (in development)
A simple and configurable command line time tracker.

##Installation

```
gem install tracking
```

##Features
- concise and configurable display
- simple syntax
- portable data

##Ideas (future)
- hashtag-like tags for organizing tasks
- different ways to view your data

##Tutorial
```
$ tracking essay for English class
+-------+------------------------------------------+----------+
| start |                   task                   | elapsed  |
+-------+------------------------------------------+----------+
| 12:00 | essay for English class                  | 00:00:00 |
+-------+------------------------------------------+----------+
$ tracking getting distracted on Reddit
+-------+------------------------------------------+----------+
| start |                   task                   | elapsed  |
+-------+------------------------------------------+----------+
| 12:00 | essay for English class                  | 00:00:20 |
| 12:20 | getting distracted on Reddit             | 00:00:00 |
+-------+------------------------------------------+----------+
$ tracking
+-------+------------------------------------------+----------+
| start |                   task                   | elapsed  |
+-------+------------------------------------------+----------+
| 12:00 | essay for English class                  | 00:00:20 |
| 12:20 | getting distracted on Reddit             | 00:00:05 |
+-------+------------------------------------------+----------+
$ tracking back to work
+-------+------------------------------------------+----------+
| start |                   task                   | elapsed  |
+-------+------------------------------------------+----------+
| 12:00 | essay for English class                  | 00:00:20 |
| 12:20 | getting distracted on Reddit             | 00:00:10 |
| 12:30 | back to work                             | 00:00:00 |
+-------+------------------------------------------+----------+
```

##Usage
```
Usage: tracking [mode]
                                     display all tasks
    <task>                           start a new task with the given text
    -c, --clear                      delete all tasks
    -d, --delete                     delete the last task
    -e, --edit                       open data file in a text editor
    -h, --help                       displays this help information
```


##Contributing to tracking
- Check out the latest master to make sure the feature hasn't been implemented or the bug hasn't been fixed yet.
- Check out the issue tracker to make sure someone already hasn't requested it and/or contributed it.
- Fork the project.
- Start a feature/bugfix branch.
- Commit and push until you are happy with your contribution.
- Make sure to add tests for it. This is important so I don't break it in a future version unintentionally.
- Please try not to mess with the Rakefile, version, or history. If you want to have your own version, or is otherwise necessary, that is fine, but please isolate to its own commit so I can cherry-pick around it.

##Similar Projects
- [timetrap](https://github.com/samg/timetrap)
- [d-time-tracker](https://github.com/DanielVF/d-time-tracker)

##Copyright
Copyright (c) 2012 Nicolas McCurdy. See LICENSE.txt for
further details.

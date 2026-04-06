1. [ ]  
---
# Today notes
``` dataview
table FileName, CreateDay
from ""
where file.cday = date(2025-02-03)
sort file.name asc
```
---
# Yesterday overdue tasks
```dataview
task
from ""
where file.day = date(yesterday)
and !completed
```


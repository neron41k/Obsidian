# Uncompleted Tasks
```dataview
table FileName, length(file.tasks) as "Tasks"
from ""
where any(file.tasks, (t) => !t.completed)
```
---

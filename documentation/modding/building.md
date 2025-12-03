# Building Your First Mod
it's pretty easy to use JSON/JSON5 so we're going to give you a bit of a crash course into it.
## The Crash Course Of JSON (Javascript Object Notation)
### value types
JSON has different value types or
* strings (```"string": "hello world",```)
* numbers (```"string": 0,```)
* objects (```"object": {"Nested value": "hello"}```)
* arrays (```"array": [0,1,2,3,"..."]```),

### rules
usually for value and key pairs that aren't the last have to have a comma afterwards Therefore, 
``` "username": "developer001" "creation-date": "1-1-2000 9:00 AM CMT" ``` isn't legal but  ``` "username": "developer001", "creation-date": "1-1-2000 9:00 AM CMT" ``` is legal, 

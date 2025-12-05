<hr>

<div align="center">

# exam
Exam Scheduler using SQLite3!

### Shell Command
Can be placed in `/usr/local/bin` (with root permission) to be used with the shell.  If problems with running occur, try to change execution permission via `sudo chmod +x /usr/local/bin/exam`.

## SQLite Database
The `exam.db` file will be stored in `/home/<username>/.config` on Linux, and `C:\Users\<username>\AppData\Local` on Windows.

## Flags

</div>

```
usage: exam [-h] {insert,show,delete} ...
                        
Exam Scheduler using SQLite3
                        
positional arguments:
	{insert,show,delete}
		insert              Insert a new exam record
		show                Show all exams
		delete              Delete exams for a course
                        
options:
	-h, --help            show this help message and exit
```

<div align="center">

## Dependencies

</div>

### Python Packages

- colorama: Library for colored terminal text output.  Install using `pip install colorama`

<hr>

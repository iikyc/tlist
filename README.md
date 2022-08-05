# tlist
tlist is a command line script used to create, delete and keep track of to-do list items.

## Installation

1. Download the script file: tlist
2. Place the script in your $PATH
3. Change the file permissions to allow execution
```bash
chmod u+x /path/to/script/file # for your user only
#or
chmod +x /path/to/script/file # for all users
```

## Usage

```bash
# add a task
tlist add "get groceries"

# mark a task as done
tlist done "get groceries"

# view all tasks
tlist list
```

tlist will create a "tasks.txt" file on your desktop, in order to change the default directory, open the script using an editor and change the following line:

```bash
tasks_file="$HOME/Desktop/tasks.txt"
```

Example:
```bash
tasks_file="$HOME/Documents/tasks.txt"
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

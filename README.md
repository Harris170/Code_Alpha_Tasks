# Code_Alpha_ToDoList

Minimal to do list console app.


![Screenshot 2024-04-14 023423](https://github.com/Harris170/Code_Alpha_ToDoList/assets/104685376/5c172c93-7694-4194-86a2-873e4d3cd6b1)

___

## 1. Help Command
Type `h` or `?` to see the help and list of commands.


![Screenshot 2024-04-14 023436](https://github.com/Harris170/Code_Alpha_ToDoList/assets/104685376/05dd283e-906e-4399-bfed-0a2b1b1a08af)

## 2. Creating a new task
`t`

This command is for making a new task.

`t this a new task`

### Creating a task with description
Writing the `-d` flag after the writing the name of the task, will let you write the description.

`t this is another task -d everything here is the description of the task i wrote`

## 3. Show tasks
`s`

This will show all available tasks.

### Show only Waiting tasks
`s w`

This will show only the tasks with the **Waiting** (or not done) status.

### Show only In Progress tasks
`s p`

Similarily, this will show only the tasks with the **In Progress** status.

### Show only Done tasks
`s d`

And this will show only the tasks with the **Done** status.

## 4. Remove a task
`r 1`

The number provided is the ID of the task that you want to remove.

### Remove all tasks at once
`r all`

Will remove all the tasks that are in the list at once, and reset the UID for the task, starting them again from ID of 1.

## 5. Set Task to Done / In Progress / Waiting
`d 1`

This will set the given ID of the task to done. Multiple IDs can be provided inline to set them all to done at the same time, like this

`d 1 3 5 7`

Similarily for setting to In Progress

`p 3`

Where 3 is the ID of the task. Inlining multiple IDs work here as well.

For setting to Waiting

`w 2`

## 6. Saving and Quitting
Entering `q` will save the tasks as Todos.md file , which can be seperately edited and can be viewed as well.  There is no importing yet.

Example file

![Screenshot 2024-04-14 023505](https://github.com/Harris170/Code_Alpha_ToDoList/assets/104685376/5016f769-8ffb-43b6-8a8a-32131c9df341)


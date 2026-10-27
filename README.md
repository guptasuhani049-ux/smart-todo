# Smart To-Do

A to-do list web app built to demonstrate **Data Structures** with a clean, modern UI.
Plan • Organize • Achieve

## Features
- Add, edit, delete and complete tasks (with deadline and priority)
- Search by task name or ID, filter by status/priority, sort by priority / deadline / name
- Undo any change
- Tasks are saved in the browser (localStorage)
- Live "Data Structures Used" panel showing what each structure is doing

## Data Structures Used
| Structure | Where it is used |
|---|---|
| Array / ArrayList | Holds the tasks that are rendered on screen |
| Linked List | Main task storage (dynamic add / remove) |
| Queue | Pending tasks in FIFO order (front = oldest pending task) |
| Stack | Undo operation (LIFO snapshots) |
| Priority Queue / Min-Heap | Finds the most urgent pending task |
| Merge Sort | Sorting by priority / deadline / name, O(n log n) |
| Searching | Find task by name or ID |

All data structures are implemented from scratch in `index.html` (no libraries).

## Run
Just open `index.html` in any browser. No install needed.

# KanbanBoard Application Specification

### Tool:
![TestLink](https://img.shields.io/badge/TestLink-yellow?style=flat?logo=TestLink)

## Overview
The Kanban Board application, available at [http://kanbanboard.pl/](http://kanbanboard.pl/), is a simple tool to manage tasks using a customizable workflow. It features a corkboard-style interface with default columns:

- **To Do**
- **Doing**
- **Done**

Upon visiting the site, users will see:
- One default task ("new task") in the **To Do** column.
- A button to add a new column ("Add New Column").
- Buttons to add new tasks ("Add Task").

Each user can customize the workflow by:
- Adjusting the number and names of columns.
- Defining the task flow between columns.

### Key Design Notes
- The **Doing** column should ideally contain between 1 and 3 tasks per person to avoid overcrowding.

---

## Application Features

### Adding a New Column
- Click the "Add New Column" button to create a new column.
- Enter a name for the column, then:
  - Click **OK** to add the column.
  - Click **Cancel** to abandon the action.
- New columns are always added to the rightmost position.

### Adding New Tasks
- Each column has an "Add Task" button.
- To create a task:
  - Click "Add Task" and enter the task name.
  - Click **OK** to confirm or **Cancel** to discard.
- Tasks can also be added without entering text, in which case they will be created as empty.
- Columns created without a name will default to **Column**.

### Drag-and-Drop Functionality
- Tasks can be moved between columns using drag-and-drop.
- Columns can also be rearranged via drag-and-drop.

### No Restrictions
- No limitations on:
  - The number of columns or tasks.
  - The length of column names or task descriptions.
- Column and task names can include any characters, including special and diacritical characters.
- Uniqueness is not enforced; duplicate names for columns or tasks are allowed.
- Columns and tasks cannot be edited but can be deleted using the **<X>** button.

### Individualized Boards
- The application relies on cookies, ensuring that each user has their own personalized board.
- There is no registration or login functionality.

---



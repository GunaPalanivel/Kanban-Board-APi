1. API Endpoints to Implement.

a. Add a column to a board -> POST/boards/{board_id}/columns

b.Add a Task to a Column -> POST/columns/{column_str_id}/tasks

c.List Tasks in a Column -> GET/columns/{column_str_id}/tasks

d.Move a Task to a Different Column -> PUT/tasks_column_str_id}/move

e.Reorder a Task Within the Column -> PUT/tasks_column_str_id}/reorder

f. Fetch Full Boards View -> GET/boards/{board_id}/view

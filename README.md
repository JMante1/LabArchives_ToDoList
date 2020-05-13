# LabArchives_ToDoList
To do list widget for LabArchives. Enter your tasks seperated by enters and the widget will transform them into a list of tasks with check boxes next to them.

# Install
Open the Widgets manager in LabArchives. Create a new custom widget. Paste html_code in Widgeth Html editor Source, and the script_code in the script editor (make sure both are blank before pasting any code in).

# Customisation
Currently tasks are separated by enters (represented as \n in the code). This can be changed by altering the line of code in script_code.js: `var splittodo = todolist.split("\n");`. Enter (\n) can be replaced by commas, dashes, dash enters, etc.

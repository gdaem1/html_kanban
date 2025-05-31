# html_kanban
A Kanban board helps track tasks for work you are doing. They are commonly used in software development and are often tied to a larger system for a code base. This kanban is not like that.


This kanban-style board is a simple, clean, and low-feature task tracker built entirely in HTML, CSS, and JS. This allows the application to run in a browser on your computer. 
It should be able to run in secure environments because it does not require access to the internet or additional security measures.

This application uses an unreliable persistent state to track your changes. Tasks are saved to the LocalStorage file in your browser. Therefore, if you delete your browser history, cookies, and/or cache, you will lose your tasks.

To prevent this, the application provides the ability to export your tasks to a JSON file for backup. To restore your tasks, simply import the JSON file. 

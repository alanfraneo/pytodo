# pytodo
a simple todo app using python

# Basic Idea

Create a todo app using python + Django backend and js frontend.

# Ideas / Use Cases

1. No databases, decrease complexity and use JSON flat files
2. The todo item has: a rich text field, a priority, created date, last modified date, and a completed flag.
3. When a todo item is marked as complete, move it to the bottom of the list and put a strikeout style for the text, the latest todo item to be marked as completed should be on top of all the previous completed items.
4. When a completed item, is unmarked again to become an pending todo item, revert to the previous position in the list.

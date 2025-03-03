# Messing around with Cursor

This repo is to just fiddle around with Cursor and other AI related technologies.

## Notes:

To gauge the extent of Cursor's capabilities, I attempted to get to create the project from scratch.
Prompt supplied: `Create a new react application, using vite and integrate with tailwind`
Cursor managed to run the relevant npm commands to create a new React application with Vite. However, it did encounter several errors with read-only permissions on the files created. It kind of got stuck in a loop and did not know how to resolve those issues.
I manually created the React & Vite project structure, and it took less time than trying to prompt Cursor to fix the mess it had gotten itself into.

But maybe, that is not a fair use case for Cursor. I then prompted it to integrate Tailwind in the fresh React & Vite project. It could not do this either, as it tried to integrate Tailwind in a way that did not suit the project structure. There were several errors with the first approach it implemented. The second solution that it came up with also had issues. I reverted it's changes and implemented Tailwind manually.

So, currently, Cursor is 0/2 for setting up a fresh project.

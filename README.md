# Stack-Based-Text-Editor
## Background
The Stack-Based Text Editor is a console-based project that demonstrates efficient text manipulation using data structures. It supports basic editing operations such as insert, delete, and replace, along with undo and redo features powered by stacks. The use of a linked list for storing text ensures flexibility and efficient handling of lines
## Objective
To develop a text editor that supports text insertion, deletion, and replacement.

To implement undo and redo operations using stacks.

To allow saving, clearing, and managing text files efficiently.
## Problem Statement
Traditional editors face challenges in managing undo/redo operations efficiently. This project uses stacks and linked lists to overcome these limitations by allowing users to:

Undo or redo their last changes.

Dynamically manage text lines.

Save and clear the editor content easily.
## Features
Insert new lines of text at specific positions.

Delete or replace existing lines.

Undo and redo the most recent operations.

Save the text document to a file.

Clear all editor content and start fresh.
## Methadology
The program uses a linked list to store text lines dynamically.

Stacks are used to manage undo and redo operations.

Undo Stack: To record and reverse user operations.

Redo Stack: To reapply undone operations when needed.
## Steps of Operation
Insert text at a specified line number.

Delete or replace a line as required.

Undo to revert the last operation.

Redo to restore an undone change.

Save current content to a text file.

Clear all lines to reset the editor.
# How to Run
Compile and run the program in any C++ environment.

Use the on-screen menu to perform operations such as insert, delete, replace, undo, redo, save, and clear
